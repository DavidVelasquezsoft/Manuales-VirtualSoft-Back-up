# documentación de código pruebas automatizadas

> **Stack:** Playwright · Cucumber · TypeScript · Page Object Model
>
> Guía de referencia para documentar todos los archivos del proyecto. Cada sección incluye la plantilla a seguir y un ejemplo aplicado que muestra cómo se ve esa plantilla en un caso práctico.

***

### Reglas generales

1. Describe el propósito y la funcionalidad del código, evitando documentar su tipo, ya que TypeScript lo especifica de forma explícita.
2. Cuando el nombre del método ya comunica con claridad lo que hace, no es necesario añadir un comentario.
3. Los elementos opcionales (`?`) y las condiciones específicas por país deben documentarse siempre, ya que representan decisiones de implementación que no son evidentes.
4. Los comentarios de sección (`// === Nombre ===`) agrupan visualmente el código sin necesidad de texto adicional y deben mantenerse iguales en todas las capas de un mismo módulo, de modo que el mismo elemento se localice en el mismo bloque al pasar de la interfaz al locator y al component.
5. Los _inline comments_ se reservan para situaciones donde hay una solución alternativa, una restricción oculta o un comportamiento que puede sorprender a quien lea el código.
6. El bloque de módulo (`/** ... */` antes del export principal) es **obligatorio** en todos los archivos. El resto de comentarios aplica según las reglas de cada capa.

***

### Tags JSDoc — cuándo usar cada uno

<table><thead><tr><th width="129.99993896484375">Tag</th><th>Cuándo usarlo</th><th>Ejemplo</th></tr></thead><tbody><tr><td><code>@param</code></td><td>Se documenta únicamente cuando el parámetro no es evidente por su nombre o cuando su impacto es amplio. Los parámetros <code>page</code> y <code>site</code> no se documentan, ya que son convención del framework. <code>country</code> sí se documenta siempre, porque afecta selectores, comportamientos y elementos disponibles.</td><td><code>@param country País de la sesión activa este afecta selectores y elementos visibles (PE | CL | GT)</code></td></tr><tr><td><code>@returns</code></td><td>Se usa solo cuando el tipo de retorno no explica suficientemente el valor. <code>Promise&#x3C;void></code> no necesita documentación. En cambio, <code>Promise&#x3C;boolean></code> donde <code>true</code> significa "navegó a otra página", o <code>Promise&#x3C;number></code> para un monto numerico, sí deben documentarse.</td><td><code>@returns Monto del bono como número sin formato</code></td></tr><tr><td><code>@throws</code></td><td>Se incluye cuando el método lanza un error de manera intencional y el motivo no es evidente.</td><td><code>@throws Error si el texto del monto no puede obtenerse como número</code></td></tr><tr><td><code>@see</code></td><td>Se usa cuando un método depende del estado que dejó otro método de la misma clase.</td><td><code>@see clickOnClaimBonusButton — captura el estado previo en initialBonusState</code></td></tr></tbody></table>

{% hint style="warning" %}
**Nota:** Omite la documentación de `@param page` y `@param site`, ya que son parámetros propios del framework. Documenta siempre `@param country`, ya que su comportamiento tiene un impacto funcional significativo.
{% endhint %}

***

### Capa 1 — Interfaces (`*.interfaces.ts`)

Las interfaces definen la estructura que deben seguir los selectores de cada módulo. Describe el propósito general de la interfaz y documenta únicamente los campos cuyo significado no sea evidente, sean opcionales o dependan del sitio o país.

Los campos opcionales (`?`) indican que el elemento no existe en todos los sitios o países, por lo que su ausencia es intencional y válida. Antes de interactuar con ellos es necesario verificar que no sean `undefined`. A esta verificación se le llama **guard** en la capa Component/Page:

```typescript
// Ejemplo de guard en Component
const el = this.locators.campoOpcional;
if (!el) return; // ← esto es el guard
await el.click();
```

#### Plantilla

```typescript
/**
 * [Descripción de la interfaz — qué elementos o comportamientos agrupa].
 *
 * [Solo si hay campos opcionales]:
 * Los campos opcionales (`?`) no existen en todos los sitios o países.
 * Deben verificarse con guard (`if (!locator) return;`) antes de usarse en [Component/Page].
 */
export interface NombreSelectors {

    // === Sección temática ===

    /** Descripción del campo si no es obvia por el nombre */
    campo: Locator;

    /** Solo disponible en [sitio / país / condición que aplica] */
    campoOpcional?: Locator;

    /**
     * [Descripción cuando necesita más contexto].
     * Sin `param` retorna todos los elementos. 
     * Con `param` filtra por ese valor.
     */
    campoFuncion: (param?: string) => Locator;
}
```

#### Ejemplo aplicado

Interfaz de la **barra de promociones**, un módulo que muestra las ofertas activas al usuario y permite reclamar bonos.

```typescript
/**
 * Define la estructura de selectores de la barra de promociones
 * para todos los sitios soportados.
 *
 * Los campos opcionales (`?`) no existen en todos los sitios o países.
 * Deben verificarse con guard antes de usarse en PromoBarComponent.
 */
export interface PromoBarSelectors {

    /** Elemento raíz de la barra — se usa para verificar que la sección cargó */
    promoBarLocator: Locator;

    // === Acciones principales ===
    claimBonusButton: Locator;
    seeTermsButton: Locator;

    /**
     * Botón para ver el detalle de los requisitos del bono.
     * Solo disponible en PE.
     */
    requirementsButton?: Locator;

    // === Datos de la promoción ===
    /** Monto del bono disponible, mostrado como texto con símbolo de moneda */
    bonusAmount: Locator;

    /**
     * Contador interno con el tiempo restante de la promoción.
     * Se usa para leer el valor antes y después de reclamar el bono.
     * Solo disponible en DORADOBET.
     */
    countdownTimer?: Locator;

    /**
     * Tarjeta de una promoción dentro de la barra.
     * Sin `promoName` retorna todas las tarjetas visibles.
     * Con `promoName` filtra la tarjeta que contiene ese texto.
     */
    promoCard: (promoName?: string) => Locator;
}
```

***

### Capa 2 — Selectores (`selectors/*.ts`)

El bloque de documentación del módulo es **obligatorio**. Para el resto, aplica una única regla: **si el código se entiende por sí mismo, no requiere comentarios**. Documenta únicamente aquello que aporte contexto no visible en el código, como reglas de negocio, diferencias por país o comportamientos externos.

En general, **deben documentarse**:

* Selectores complejos (XPath, `nth` o atributos poco comunes).
* Elementos cuyo comportamiento varía según el país o que pueden ser `undefined`.

No requieren documentación:

* Locators y variables cuyo propósito sea evidente.
* Campos de tipo función cuyo comportamiento ya esté documentado en la interfaz.

Los comentarios se escriben con `//`. El bloque `/** */` se reserva para la función exportada y para los helpers con nombre.

Los separadores `// === Nombre ===` solo deben utilizarse en objetos anidados extensos, como mapas de enlaces o proveedores.

En el bloque del módulo, documenta únicamente las diferencias estructurales o de comportamiento entre países. Las variaciones de texto deben comentarse únicamente donde ocurren.

{% hint style="info" %}
**Campos que no existen en un sitio:** cuando un elemento no está presente en el sitio, el campo simplemente se omite del archivo de selectores. No es necesario escribirlo con valor `undefined`, ya que la interfaz lo declara como opcional y eso basta para que TypeScript lo permita.
{% endhint %}

#### Plantilla — función simple

```typescript
/**
 * Selectores de [módulo] para [SITIO] ([países si aplica]).
 *
 * Variaciones por país:
 * - [País A]: [diferencia estructural o de comportamiento].
 * - [País B]: [diferencia estructural o de comportamiento].
 *
 * [Si aplica] No incluye [campos] ya que [razón concreta].
 *
 * @param country País de la sesión actual — afecta selectores y elementos disponibles
 */
export const sitioNombreSelectors = (page: Page, country: CountryCode): NombreSelectors => ({
    campo: page.locator('selector'),

    // [País A] usa [X]; [País B] usa [Y]
    campoCondicional: country === 'PE'
        ? page.locator('selector-pe')
        : page.locator('selector-otro'),

    // XPath necesario — el elemento no tiene id ni atributo data-* propio
    campoXPath: page.locator('xpath=//...'),

    // Solo disponible en PE
    campoOpcional: country === 'PE'
        ? page.locator('selector')
        : undefined,
});
```

#### **Ejemplo aplicado — función simple**

Selectores de la **barra de promociones** para un sitio que opera en tres países.

```typescript
/**
 * Selectores de la barra de promociones para DORADOBET (PE | CL | GT).
 *
 * Variaciones por país:
 * - PE: la promoción se llama "bono de bienvenida"; incluye requirementsButton.
 * - CL / GT: la promoción se llama "bono inicial"; sin requirementsButton.
 *
 * No incluye promoFilters ya que la barra de este sitio muestra todas
 * las promociones sin opción de filtrado.
 *
 * @param country País de la sesión actual — afecta selectores y elementos disponibles
 */
export const doradobetPromoBarSelectors = (page: Page, country: CountryCode): PromoBarSelectors => ({
    promoBarLocator: page.locator('[data-testid="promo-bar"]'),
    bonusAmount:     page.locator('[data-testid="promo-bar"] span.bonus-amount'),

    // PE nombra la promoción "bono de bienvenida"; CL y GT la nombran "bono inicial"
    claimBonusButton: page.getByRole('button', {
        name: country === 'PE' ? 'Reclamar bono de bienvenida' : 'Reclamar bono inicial', exact: true
    }),

    // XPath necesario — el contador se renderiza en un span sin id ni data-* propio
    countdownTimer: page.locator('xpath=//div[@data-testid="promo-bar"]//span[contains(@class,"timer")]'),

    // nth(1) porque nth(0) corresponde al botón de cerrar la barra
    seeTermsButton: page.locator('[data-testid="promo-bar"]').getByRole('button').nth(1),

    // Solo disponible en PE
    requirementsButton: country === 'PE'
        ? page.getByRole('button', { name: 'Requisitos del bono' })
        : undefined,

    promoCard: (promoName?: string) => {
        if (!promoName) return page.locator('[data-testid="promo-card"]');
        return page.locator('[data-testid="promo-card"]').filter({ hasText: promoName });
    },
});
```

{% hint style="success" %}
No se documenta `promoCard` porque su comportamiento con y sin parámetro ya está definido en la interfaz. Mantener la descripción en un único lugar evita duplicidad y reduce el riesgo de que la documentación quede desactualizada.
{% endhint %}

#### **Plantilla — función con variables locales y objeto anidado**

Algunos selectores necesitan construir variables auxiliares antes del `return`, como el elemento raíz del módulo o un comportamiento que cambia según el país.

En estas variables la regla de comentarios es la misma que en el resto de la capa: las variables cuyo nombre ya indica qué representan no llevan comentario, mientras que las que dependen de una condición por país sí lo llevan, en la línea donde se define esa condición.

```typescript
/**
 * Selectores de [módulo] para [SITIO].
 *
 * Variaciones por país:
 * - PE: [comportamiento diferente].
 * - CL / GT: [comportamiento diferente].
 *
 * @param country País de la sesión actual — afecta comportamientos y links disponibles
 */
export const sitioNombreSelectors = (page: Page, country: CountryCode): NombreSelectors => {

    const raiz = page.locator('selector-raiz');

    // PE: [comportamiento A]; CL/GT: [comportamiento B]
    const comportamiento: TipoComportamiento = country === 'PE'
        ? { type: 'modal', verifyLocator: page.getByText('Texto', { exact: true }) }
        : { type: 'redirect', url: '/ruta' };

    return {
        raiz,
        comportamiento,
        links: {

            // === Grupo temático A ===
            'Nombre link': raiz.getByRole('link', { name: 'Nombre link' }),
            // CL usa texto diferente
            'Link condicional': raiz.getByRole('link', {
                name: country !== 'CL' ? 'Texto A' : 'Texto B'
            }),

            // === Grupo temático B ===
            // Se localiza por href — el texto varía según idioma
            'Link por href': raiz.locator('a[href*="dominio.com"]'),
            // Solo disponible en PE y GT
            'Link exclusivo': country !== 'CL'
                ? raiz.getByRole('link', { name: 'Link exclusivo' })
                : undefined,
        },
    };
};
```

#### **Ejemplo aplicado — función con variables locales**

Selectores de la **sección de métodos de pago**, donde cada país tiene proveedores distintos y el botón de ayuda se comporta de forma diferente según la regulación local.

```typescript
/**
 * Selectores de la sección de métodos de pago para DORADOBET (PE | CL | GT).
 *
 * Variaciones por país:
 * - PE: la ayuda de recargas abre un modal; incluye la red de agentes autorizados.
 * - CL: la ayuda de recargas redirige a términos y condiciones; el proveedor regional
 *   se comercializa bajo el nombre local "PagoRápido".
 * - GT: la ayuda de recargas redirige a términos y condiciones; sin débito inmediato,
 *   ya que el proveedor aún no tiene convenio en el país.
 *
 * @param country País de la sesión actual — afecta comportamientos y proveedores disponibles
 */
export const doradobetPaymentMethodsSelectors = (page: Page, country: CountryCode): PaymentMethodsSelectors => {

    const section = page.locator('[data-testid="payment-methods"]');

    // PE abre un modal en la misma página; CL y GT redirigen a términos y condiciones
    const helpLinkBehavior: LinkBehavior = country === 'PE'
        ? { type: 'modal', verifyLocator: page.getByText('Ayuda con recargas', { exact: true }) }
        : { type: 'redirect', url: '/terminos-y-condiciones/recargas' };

    /**
     * Traduce la clave de un proveedor al locator de su botón.
     * Casi todos se localizan por `data-provider`, salvo "Efectivo en agencia",
     * que solo expone un botón "Configurar" sin atributo propio.
     */
    const resolveProviderButton = (providerKey: string) => {
        // Hay un botón "Configurar" por proveedor, por eso se acota con el logo
        if (providerKey === 'provider:configure:efectivo-agencia') {
            return section.locator('a')
                .filter({ has: section.locator('img[src*="efectivo-agencia"]') })
                .getByRole('button', { name: 'Configurar' });
        }
        return section.locator(`[data-provider="${providerKey}"]`).first();
    };

    return {
        sectionLocator: section,
        sectionTitle:   section.getByRole('heading', { name: 'Métodos de pago' }),
        helpButton:     section.getByRole('button', { name: 'Ayuda con recargas' }),
        helpLinkBehavior,

        // "Efectivo en agencia" no tiene data-provider — ver resolveProviderButton
        providerButton: (providerKey) => resolveProviderButton(providerKey),

        paymentProviders: {

            // === Billeteras digitales ===
            'Billetera Global': section.getByRole('button', { name: 'Billetera Global' }),
            // CL usa el nombre comercial local en lugar del nombre regional
            'Pago Express': section.getByRole('button', {
                name: country !== 'CL' ? 'Pago Express' : 'PagoRápido'
            }),

            // === Transferencias bancarias ===
            // Se localiza por data-provider porque el logo no tiene texto visible
            'Transferencia bancaria': section.locator('[data-provider="bank-transfer"]'),
            // No disponible en GT
            'Débito inmediato': country !== 'GT'
                ? section.getByRole('button', { name: 'Débito inmediato' })
                : undefined,

            // === Efectivo en punto físico ===
            // Exclusivo PE: red de agentes autorizados por el regulador local
            'Agentes autorizados': country === 'PE'
                ? section.getByRole('button', { name: /Agentes autorizados/i })
                : undefined,
        },
    };
};
```

***

### Capa 3 — Locators (`*Locators.ts`)

Esta capa actúa como adaptador entre los selectores y las páginas o componentes, exponiendo getters y métodos tipados para evitar que la capa superior acceda directamente a los selectores.

**Reglas de documentación:**

* El bloque del módulo debe limitarse a una única línea que indique a qué módulo pertenecen los selectores.
* Los getters que retornan `Locator` no requieren documentación cuando su propósito sea evidente.
* Los getters que retornan `Locator | undefined` deben indicar en qué sitio o país están disponibles.
* Los métodos con parámetros o lógica propia deben documentar el propósito de los parámetros y el valor retornado cuando no sea evidente.
* Los separadores `// === Nombre ===` deben utilizarse para agrupar getters relacionados, ya que estas clases funcionan como un catálogo de elementos y la agrupación facilita su localización.

**Plantilla**

```typescript
/** Localizadores del [módulo] para el sitio activo. */
export class NombreLocators {

    // === Sección temática ===
    get campo(): Locator                     { return this.selectors.campo; }
    /** Solo disponible en [sitio / país] */
    get campoOpcional(): Locator | undefined { return this.selectors.campoOpcional; }

    /**
     * Retorna el locator del elemento por su nombre clave.
     * Retorna `undefined` si el elemento no existe en el país actual.
     */
    getElemento(nombre: string): Locator | undefined {
        return this.selectors.mapa?.[nombre];
    }

    /**
     * Retorna todos los locators definidos para el país actual.
     * Excluye automáticamente los valores `undefined`.
     */
    get getAll(): Locator[] { ... }
}
```

**Ejemplo aplicado**

Locators de la **sección de métodos de pago**, que expone tanto getters directos como métodos con lógica para trabajar con el listado de proveedores.

```typescript
/** Localizadores de la sección de métodos de pago para el sitio activo. */
export class PaymentMethodsLocators {

    // === Estructura ===
    get sectionLocator(): Locator         { return this.selectors.sectionLocator; }
    get sectionTitle(): Locator           { return this.selectors.sectionTitle; }
    /** Solo disponible en DORADOBET */
    get helpButton(): Locator | undefined { return this.selectors.helpButton; }

    // === Proveedores de pago ===

    /**
     * Retorna el locator de un proveedor de pago por su nombre visible.
     * Retorna `undefined` si el proveedor no está habilitado en el país actual.
     */
    getProvider(providerName: string): Locator | undefined {
        return this.selectors.paymentProviders?.[providerName];
    }

    /**
     * Retorna todos los locators de proveedores habilitados en el país actual.
     * Los proveedores con valor `undefined`, es decir, los que no aplican
     * al país, quedan excluidos del resultado.
     */
    get getAll(): Locator[] {
        const locators: Locator[] = [];
        if (this.selectors.paymentProviders) {
            locators.push(
                ...Object.values(this.selectors.paymentProviders)
                    .filter((l): l is Locator => l !== undefined)
            );
            return locators;
        }
        return Object.values(this.selectors) as Locator[];
    }

    // === Comportamientos ===

    /** Solo disponible en DORADOBET — ECUABET no varía el comportamiento de la ayuda */
    get helpLinkBehavior(): LinkBehavior | undefined {
        return this.selectors.helpLinkBehavior;
    }
}
```

***

### Capa 4 — Pages & Components (`*Page.ts` / `*Component.ts`)

Aquí reside la lógica de interacción con la interfaz. Todas las clases extienden `BasePage`, que provee los métodos base como `clickOn`, `verifyIsVisible`, `verifyIsNotVisible` y `hoverOn`.

**Reglas de documentación:**

* Del bloque de módulo solo es obligatoria la primera línea, que indica qué es el componente o la página. La lista de flujos principales se añade únicamente cuando hay varios o alguno tiene lógica no evidente.
* Las propiedades que guardan estado entre métodos se documentan siempre, indicando dónde se asignan y dónde se consumen.
* Los métodos que solo delegan en `BasePage` no llevan comentario cuando su nombre lo explica todo.
* Cuando un método recibe un `DataTable`, documenta con `@param` las columnas que espera. La firma no las revela y un nombre distinto en el feature provoca un fallo en ejecución, no en compilación.
* Sí llevan comentario los métodos con guard propio, lógica interna, valor de retorno no evidente, precondiciones o cualquier comportamiento que sorprenda al lector.

**Sobre los guards:** los métodos de `BasePage` ya verifican internamente que el locator exista, por lo que **al delegar en ellos no se escribe ningún guard**. El guard explícito solo se añade cuando el método accede al locator directamente, por ejemplo al usar `expect`, `isChecked` o `innerText`. En ese caso se documenta indicando que el guard es propio.

{% hint style="danger" %}
Nunca usar `!` (_non-null assertion_) sobre un campo opcional para evitar el error de tipos. La forma correcta es verificar con `if (!el) return;`, ya que el `!` oculta el problema y provoca fallos difíciles de rastrear en los sitios donde el elemento no existe.
{% endhint %}

**Plantilla**

```typescript
/**
 * [Qué es este componente o página].
 *
 * Flujos principales:    ← solo si hay varios o alguno tiene lógica no evidente
 * - [Nombre del flujo]: [qué cubre]
 * - [Nombre del flujo]: [qué cubre]
 */
export class NombreComponent extends BasePage {

    /**
     * [Qué almacena].
     * Se asigna en `metodoA` y se consume en `metodoB`.
     */
    private estadoInterno!: boolean;

    // === Sección temática ===

    // Delega en BasePage y el nombre lo explica → sin comentario
    async verifyAlgoIsVisible() {
        await this.verifyIsVisible(this.locators.campo);
    }

    // Locator opcional delegado en BasePage → tampoco lleva guard ni comentario
    async clickOnCampoOpcional() {
        await this.clickOn(this.locators.campoOpcional);
    }

    /**
     * [Qué hace y qué deja preparado].
     * Guard propio: accede al locator directamente en lugar de usar `BasePage`.
     *
     * @see metodoB - consume el estado capturado aquí
     */
    async metodoConEstado() {
        const el = this.locators.campoOpcional;
        if (!el) return;
        this.estadoInterno = await el.isChecked();
    }

    /**
     * [Qué hace, cuando el nombre no basta o hay un efecto secundario].
     *
     * @param param [Solo si el parámetro no es evidente]
     * @returns [Solo si el tipo no explica el valor]
     * @throws Error [Cuándo y por qué]
     */
    async metodoConLogica(param: string): Promise<number> { ... }
}
```

**Ejemplo aplicado**

Componente de la **barra de promociones**, que reúne los casos más frecuentes: métodos simples, un locator opcional delegado, dos métodos que comparten estado, un recorrido con `DataTable` y un método que convierte texto a número.

```typescript
/**
 * Acciones e interacciones de la barra de promociones para DORADOBET.
 *
 * Flujos principales:
 * - Consulta: verificar que la barra cargó y que las promociones se visualizan
 * - Reclamo de bono: reclamar la promoción activa y comprobar que el contador se detuvo
 * - Requisitos: abrir el detalle de requisitos exigido por el regulador local
 */
export class PromoBarComponent extends BasePage {

    /**
     * Texto del contador antes de reclamar el bono.
     * Se asigna en `clickOnClaimBonusButton` y se consume en `verifyCountdownStopped`.
     */
    private initialCountdownText!: string;

    // === Verificaciones ===

    async verifyPromoBarIsVisible() {
        await this.verifyIsVisible(this.locators.promoBarLocator);
    }

    // === Reclamo del bono ===

    async clickOnRequirementsButton() {
        await this.clickOn(this.locators.requirementsButton);
    }

    /**
     * Guarda el valor actual del contador y pulsa el botón de reclamo.
     * El valor previo queda en `initialCountdownText` para la verificación posterior.
     * Guard propio: lee el texto del contador directamente, sin pasar por `BasePage`.
     *
     * @see verifyCountdownStopped - consume el valor capturado aquí
     */
    async clickOnClaimBonusButton() {
        const timer = this.locators.countdownTimer;
        if (timer) this.initialCountdownText = await timer.innerText();
        await this.clickOn(this.locators.claimBonusButton);
    }

    /**
     * Verifica que el contador se detuvo comparando contra el valor previo al reclamo.
     * Guard propio: usa `expect` sobre el locator directamente.
     *
     * @see clickOnClaimBonusButton - captura el valor previo en `initialCountdownText`
     */
    async verifyCountdownStopped() {
        const timer = this.locators.countdownTimer;
        if (!timer) return;
        await expect(timer).toHaveText(this.initialCountdownText);
    }

    /**
     * Recorre cada fila del DataTable entrando a la tarjeta de promoción y comprobando
     * que se abra su detalle. Tras cada verificación vuelve atrás para dejar la barra
     * lista para la siguiente vuelta.
     *
     * @param dataTable Columna `promoción`
     */
    async clickAndVerifyEachPromo(dataTable: DataTable) { ... }

    /**
     * Lee el monto del bono disponible y lo convierte a número.
     * Elimina el símbolo de moneda y los separadores de miles antes de parsear.
     *
     * @returns Monto del bono como número sin formato
     * @throws Error si el texto del monto no puede convertirse a número
     */
    async getBonusAmount(): Promise<number> {
        const text = await this.locators.bonusAmount.innerText();
        const parsed = parseFloat(text.replace(/[^0-9.]/g, ''));
        if (isNaN(parsed)) throw new Error(`No se pudo leer el monto del bono: "${text}"`);
        return parsed;
    }
}
```

***

### Capa 5 — Features (`.feature`)

Los archivos Gherkin son documentación en sí mismos, por lo que el estándar en esta capa es de **estructura**, no de comentarios adicionales.

#### Tags de país

Cada país tiene su propio tag, formado por el código de dos letras del país al que pertenece:

<table><thead><tr><th width="328">Tag</th><th>País</th></tr></thead><tbody><tr><td><code>@PE</code></td><td>Perú</td></tr><tr><td><code>@CL</code></td><td>Chile</td></tr><tr><td><code>@GT</code></td><td>Guatemala</td></tr><tr><td><code>@EC</code></td><td>Ecuador</td></tr></tbody></table>

Estos tags determinan en qué país se ejecuta cada escenario:

| Situación                              | Tag                         |
| -------------------------------------- | --------------------------- |
| El escenario aplica a todos los países | Sin tag                     |
| Solo aplica a un país                  | `@PE`, `@CL`, `@GT` o `@EC` |
| Aplica a dos países específicos        | `@PE @GT` (los dos juntos)  |

Cuando el mismo flujo de negocio tiene datos o URLs diferentes por país, se crea un escenario por país con el mismo nombre y el tag correspondiente. Esto es intencional y es la forma correcta de manejar la variación entre países:

```gherkin
@PE
Scenario: Los proveedores de pago disponibles se muestran correctamente
  Then Los siguientes proveedores de pago se visualizan correctamente:
    | proveedor            |
    | Billetera Global     |
    | Agentes autorizados  |

@CL
Scenario: Los proveedores de pago disponibles se muestran correctamente
  Then Los siguientes proveedores de pago se visualizan correctamente:
    | proveedor            |
    | Billetera Global     |
    | PagoRápido           |
```

#### Plantilla

```gherkin
# ===
# Módulo  : [Nombre del módulo]
# Sitio   : [Nombre del sitio al que pertenece el feature]
# Países  : [PE | CL | GT | EC | todos]
# Alcance : [Qué cubre este feature en una línea]
# ===
Feature: [Título descriptivo del feature]

  Background:
    Given Abro y verifico si la plataforma esta abierta

  Scenario: [Resultado esperado — sin tag si aplica a todos los países]
    Given [precondición]
    When  [acción]
    Then  [verificación]

  @PE
  Scenario: [Resultado esperado — solo se ejecuta en PE]
    ...

  @PE @GT
  Scenario: [Resultado esperado — se ejecuta en PE y GT]
    ...
```

#### Ejemplo aplicado

Feature de la **sección de métodos de pago**, donde los proveedores disponibles cambian según el país y la ayuda de recargas se comporta de forma distinta.

```gherkin
# ===
# Módulo  : Métodos de pago
# Sitio   : DORADOBET
# Países  : PE | CL | GT
# Alcance : Verificación de visibilidad de proveedores y comportamiento de la ayuda de recargas.
#           Los escenarios de proveedores están separados por país porque los convenios varían.
# ===
Feature: Verificación de carga y visualización de los métodos de pago

  Background:
    Given Abro y verifico si la plataforma esta abierta
    And Inicio sesión con un usuario válido

  Scenario: Verifico que la sección de métodos de pago se visualice correctamente
    Given La sección de métodos de pago se cargó correctamente
    Then Todos los componentes de la sección se visualizan correctamente

  @PE
  Scenario: Los proveedores de pago disponibles se muestran correctamente
    Given La sección de métodos de pago se cargó correctamente
    Then Los siguientes proveedores de pago se visualizan correctamente:
      | proveedor               |
      | Billetera Global        |
      | Pago Express            |
      | Transferencia bancaria  |
      | Agentes autorizados     |

  @CL
  Scenario: Los proveedores de pago disponibles se muestran correctamente
    Given La sección de métodos de pago se cargó correctamente
    Then Los siguientes proveedores de pago se visualizan correctamente:
      | proveedor               |
      | Billetera Global        |
      | PagoRápido              |
      | Transferencia bancaria  |

  @CL @GT
  Scenario: La ayuda de recargas redirige a los términos y condiciones
    Given La sección de métodos de pago se cargó correctamente
    When Doy click en el botón de ayuda de recargas
    Then Se abre la página de términos y condiciones de recargas

  @PE
  Scenario: La ayuda de recargas abre el modal informativo
    Given La sección de métodos de pago se cargó correctamente
    When Doy click en el botón de ayuda de recargas
    Then Se muestra el modal de ayuda con recargas
```

***

### Capa 6 — Steps (`*Steps.ts`)

Los steps son el puente entre los escenarios Gherkin y el Page Object Model. No se documentan de forma individual, ya que su propósito queda definido en el texto del escenario. Solo se documenta el **bloque de módulo** con el dominio que cubre el archivo, y se añade un _inline comment_ únicamente cuando un step contiene lógica interna que no es evidente, como un retorno condicional, manejo de estado o un guard.

#### Plantilla

```typescript
/**
 * Steps de [dominio que cubre este archivo].
 * [Una línea adicional solo si hay algo relevante sobre el estado o comportamiento compartido.]
 */
import { Given, When, Then } from "@cucumber/cucumber";

// Step directo → sin comentario
When('Doy click en el botón X', async function () {
    await this.pageFactory.xComponent.clickOnX();
});

// Step con lógica interna → inline comment donde está la decisión
Then('Se verifica el resultado', async function () {
    // retorna false si el sitio no tiene esta funcionalidad
    const resultado = await this.pageFactory.xComponent.accionCondicional();
    if (resultado) {
        await this.pageFactory.xPage.verifyXPageIsOpen();
    }
});
```

#### Ejemplo aplicado

Steps de la **sección de métodos de pago**, que combinan pasos de delegación directa con un paso que contiene una decisión interna.

```typescript
/**
 * Steps de métodos de pago, proveedores y ayuda de recargas.
 * El inicio de sesión es precondición en todos los escenarios de esta sección,
 * ya que los proveedores solo se muestran con el usuario autenticado.
 */

// Step directo → sin comentario
When('Doy click en el botón de ayuda de recargas', async function () {
    await this.pageFactory.paymentMethodsComponent.clickOnHelpButton();
});

// Step con retorno condicional → comentario en la línea de la decisión
Then('El proveedor seleccionado abre su formulario correspondiente', async function () {
    await this.pageFactory.paymentMethodsComponent.verifySectionIsVisible();
    await this.pageFactory.paymentMethodsComponent.clickOnFirstAvailableProvider();
    // retorna false si el proveedor abre una pasarela externa en lugar de un formulario interno
    const abrioFormulario = await this.pageFactory.paymentMethodsComponent.verifyInternalFormOpened();
    if (abrioFormulario) {
        await this.pageFactory.depositFormPage.verifyFormIsOpen();
    }
});

// Step con DataTable → sin comentario, el nombre y el parámetro lo describen
Then('Los siguientes proveedores de pago se visualizan correctamente:', async function (dataTable) {
    await this.pageFactory.paymentMethodsComponent.verifyProvidersAreVisible(dataTable);
});
```

***

### Capa 7 — Config & Enums

Archivos de configuración y constantes compartidas. El bloque de módulo describe qué aspectos del sistema controla ese archivo. Cada valor individual se documenta únicamente cuando su nombre no es suficientemente descriptivo.

#### Config (`*.config.ts`)

```typescript
/**
 * [Qué controla este archivo].
 * Punto único de verdad para [X], por lo que cualquier cambio aquí
 * afecta a todos los sitios y países del framework.
 */

/** Sitios soportados por el framework */
export type SiteName = 'DORADOBET' | 'ECUABET' | 'PANIPLAY';

/** Países operativos — afecta selectores, proveedores de pago y textos del sitio */
export type CountryCode = 'PE' | 'CL' | 'GT' | 'EC';
```

#### Enums

```typescript
/**
 * Duraciones de espera estándar para `waitFor` y `verifyIsVisible`.
 * Centraliza los valores para evitar números fijos dispersos en el código.
 */
export enum TestDuration {
    /** Acciones rápidas como clicks y llenado de campos */
    SHORT_SECONDS  = 5_000,
    /** Apertura de modales y transiciones entre páginas */
    MEDIUM_SECONDS = 10_000,
    /** Conexiones externas como chat, iframes o servicios lentos */
    LONG_SECONDS   = 20_000,
}
```

### Control de versiones
