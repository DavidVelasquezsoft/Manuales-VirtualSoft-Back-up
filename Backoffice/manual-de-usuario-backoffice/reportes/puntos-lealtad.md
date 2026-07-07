---
description: Ajusta los puntos lealtad a los usuarios según una apuesta realizada.
---

# Puntos lealtad

#### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Puntos lealtad

***

#### 2. Visualización

<figure><img src="../../.gitbook/assets/image (40).png" alt=""><figcaption><p>Captura de pantalla #1: Documentos registrados.</p></figcaption></figure>

***

### 3. **Acciones disponibles**

<table><thead><tr><th width="163">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtrar documentos</strong></td><td>Permite aplicar filtros para realizar búsqueda de los documentos legales establecidos.</td></tr><tr><td><strong>Visualizar tabla de resultados</strong></td><td>Presenta la información del historial de saldos según los filtros aplicados.</td></tr><tr><td><strong>Exportar los resultados</strong></td><td>Exporta en formato Excel la tabla de resultados según los filtros seleccionados.</td></tr><tr><td><strong>Ajustar puntos</strong></td><td>Ajusta los puntos lealtad en la cuenta del usuario.</td></tr></tbody></table>

#### 3.1 ¿Como ajustar puntos?

Desde el botón `Ajustar puntos` despliega un pop-up con el formulario para realizar un ajuste de puntos lealtad al usuario.

<table><thead><tr><th width="114">Campo</th><th width="144">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Usuario id</code></strong></td><td>Texto</td><td>Ingresa el ID del usuario al que se le ajustarán los puntos.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Lista desplegable</td><td>Indica que tipo de apuesta se realizó para ajustar los puntos <em>(Deportivas o casino).</em></td></tr><tr><td><strong><code>Id apuesta</code></strong></td><td>Texto</td><td>Id de la apuesta por la cual se le ajustarán los puntos al usuario.</td></tr></tbody></table>

El ajuste de puntos se realiza completando el formulario con los datos del usuario, una vez enviada la información, el sistema valida los datos y asigna automáticamente los puntos de lealtad correspondientes a la cuenta del usuario.

#### **3.2 🔎Filtros principales**

<table><thead><tr><th width="93">Filtro</th><th width="163">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Id usuario</code></strong></td><td>Texto</td><td>ID del usuario a consultar.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>País al que pertenece la cuenta del usuario.</td></tr><tr><td><strong><code>Tipo</code></strong></td><td>Selector</td><td>Forma en la que se visualizará el resultado de la consulta.<br><em>(Detallado, Totales)</em></td></tr></tbody></table>

#### **3.3📊 Tabla de resultados según el tipo de consulta.**

{% tabs %}
{% tab title="Detallado" %}
<table><thead><tr><th width="122">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td>Nombre del usuario</td><td>Nombre del usuario correspondiente a la consulta.</td></tr><tr><td>Moneda</td><td>Moneda manejada por la cuenta del usuario.</td></tr><tr><td>Puntos</td><td>Cantidad total de puntos lealtad que tiene el usuario.</td></tr><tr><td>Puntos a expirar</td><td>Cantidad de puntos lealtad que están pronto a expirar y se encuentran asignados al usuario.</td></tr><tr><td>Puntos expirados</td><td>Cantidad de puntos lealtad que el usuario no utilizó y se expiraron.</td></tr><tr><td>Puntos redimidos</td><td>Cantidad total de puntos que el usuario ha redimido hasta el momento de la consulta.</td></tr></tbody></table>
{% endtab %}

{% tab title="Totales" %}
<table><thead><tr><th width="122">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td>Moneda</td><td>Moneda manejada por la cuenta del usuario.</td></tr><tr><td>Puntos</td><td>Cantidad total de puntos lealtad que tiene el usuario.</td></tr><tr><td>Puntos a expirar</td><td>Cantidad de puntos lealtad que están pronto a expirar y se encuentran asignados al usuario.</td></tr><tr><td>Puntos expirados</td><td>Cantidad de puntos lealtad que el usuario no utilizó y se expiraron.</td></tr><tr><td>Puntos redimidos</td><td>Cantidad total de puntos que el usuario ha redimido hasta el momento de la consulta.</td></tr></tbody></table>
{% endtab %}
{% endtabs %}

***

**4. Validaciones y Reglas de Negocio**

* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada dependerá de los filtros seleccionados en la consulta.

***

**5. Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 14/10/2025 | Ronald Peláez | Documento inicial  |
