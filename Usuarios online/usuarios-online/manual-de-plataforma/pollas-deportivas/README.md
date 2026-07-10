# Pollas deportivas

El módulo de [**Pollas Deportivas**](https://virtualsoft.gitbook.io/untitled/glosario#polla-deportiva) permite a los usuarios participar en competencias de predicción deportiva, donde pueden **pronosticar resultados de partidos** y competir contra otros usuarios por premios o dinero.

Las pollas pueden ser públicas o privadas, y funcionan bajo un sistema de acumulación de puntos según la precisión de los pronósticos realizados por los usuarios.

### 1. Acceso al Módulo:

**Ruta de Acceso**: Sección "**Pollas deportivas**" desde el menú principal o página de inicio.

{% hint style="warning" %}
**Nota:** El nombre de esta sección puede variar según el **partner o país**, así como su ubicación dentro de la plataforma.
{% endhint %}

***

### 2. Acciones disponibles

<table><thead><tr><th width="204.22222900390625">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><a href="./#id-4.-crear-una-polla-deportiva"><strong>Crear polla</strong></a></td><td>Permite crear y configurar una nueva competencia.</td></tr><tr><td><a href="./#id-5.-participar-en-una-polla"><strong>Participar en una polla</strong></a></td><td>Permite inscribirse en una polla existente aceptando sus condiciones.</td></tr><tr><td><strong>Editar pronósticos</strong></td><td>Permite modificar los pronósticos registrados. Está disponible únicamente hasta 1 minuto antes del inicio del partido correspondiente.</td></tr><tr><td><strong>Consultar ranking</strong></td><td>Permite visualizar la posición del usuario frente a otros participantes. Se encuentra disponible durante y después del desarrollo de la polla.</td></tr><tr><td><a href="./#id-6.-resultados-y-premios"><strong>Ver resultados y premios</strong></a></td><td>Permite visualizar los resultados reales de los partidos incluidos en la polla. Se habilita una vez iniciado el evento deportivo.</td></tr></tbody></table>

***

### 3. Flujo General de Funcionamiento

Este módulo funciona como un ciclo completo de participación que inicia desde el ingreso a la [polla](https://virtualsoft.gitbook.io/untitled/glosario#polla-deportiva) hasta la entrega de premios.

1. El usuario accede a la sección de pollas deportivas.
2. Selecciona una polla disponible o crea una nueva.
3. Realiza su inscripción (_gratuita o con costo_).
4. Registra sus pronósticos dentro de la polla.
5. Espera el inicio de los eventos deportivos.
6. El sistema bloquea modificaciones y muestra resultados progresivos.
7. Se asignan puntos según los resultados reales.
8. Se genera el ranking final de participantes.
9. Se distribuyen los premios según la posición obtenida.

***

### 4. Crear una Polla Deportiva

El usuario puede crear su propia polla personalizada realizando las siguientes acciones:

{% stepper %}
{% step %}
#### Acceder a la opción de creación

Ingrese a la sección de Penka y seleccione la opción **“Crear polla privada”**.

{% hint style="warning" %}
**Nota:** Únicamente es posible crear pollas privadas. Las pollas públicas son gestionadas exclusivamente por el proveedor Penka.
{% endhint %}
{% endstep %}

{% step %}
#### Definir la configuración de la polla:

Complete las siguientes configuraciones para crear correctamente la polla:

<table><thead><tr><th width="178.5555419921875">Configuraciones</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Modo de juego</code></strong></td><td><p>Permite seleccionar el <strong>tipo de dinámica de la polla</strong>, definiendo su estructura de participación y predicción. Opciones:</p><ul><li><strong>Torneos:</strong> incluye todos los partidos de un torneo.</li><li><strong>Combos:</strong> agrupa varios partidos en una sola predicción.</li><li><strong>Polla Flash:</strong> se basa en un único partido con múltiples predicciones.</li></ul></td></tr><tr><td><strong><code>Evento</code></strong></td><td>Permite seleccionar y configurar el evento deportivo según el modo de juego elegido, definiendo los partidos o competiciones sobre los cuales se realizarán las predicciones.</td></tr><tr><td><strong><code>Nombre de la polla</code></strong></td><td>Define el nombre identificador de la polla, permitiendo diferenciarla dentro del sistema.</td></tr><tr><td><strong><code>Entrada</code></strong></td><td>Establece el monto que cada jugador debe pagar para participar en la polla.</td></tr><tr><td><strong><code>División de premio</code></strong></td><td>Configura la distribución del premio total recaudado entre los tres primeros jugadores con mayor puntaje, asignando porcentajes que en conjunto deben sumar el 100%.</td></tr></tbody></table>
{% endstep %}

{% step %}
#### Confirmar la creación.

Revise la información configurada y confirme la creación de la polla.
{% endstep %}

{% step %}
#### Compartir el acceso con otros usuarios.

Comparta el enlace generado con otros usuarios para que puedan unirse y participar.
{% endstep %}

{% step %}
#### Participación en la polla

Una vez creada, los usuarios podrán ingresar y realizar sus predicciones según las reglas establecidas.

**Guías relacionadas:**

* [Guía de participación](./#id-5.-participar-en-una-polla)
* [Asignación de premios](./#id-6.-resultados-y-premios)
* [Reglas generales del sistema](./#id-7.-validaciones-y-reglas-de-negocio)
{% endstep %}
{% endstepper %}

***

### 5. Participar en una polla

El usuario puede participar en una polla deportiva disponible dentro de la plataforma, ya sea de tipo pública o privada, cumpliendo las condiciones de acceso, tiempo y disponibilidad definidas. Para ello, siga el siguiente flujo:

{% stepper %}
{% step %}
#### **Seleccionar la polla**

Acceda a la sección de pollas y elija una polla disponible, las cuales pueden ser:

* **Públicas:** disponibles para todos los usuarios.
* **Privadas:** requieren acceso mediante un enlace compartido por el creador.
{% endstep %}

{% step %}
#### **Revisar condiciones**

Valide la información general, como valor de entrada, reglas y cantidad de participantes.
{% endstep %}

{% step %}
#### **Confirmar inscripción**

Formalice su ingreso a la polla. Si aplica costo, este se descontará automáticamente del saldo disponible.

{% hint style="warning" %}
**Nota:** En pollas privadas, si al momento de iniciar no se alcanza el mínimo de 4 participantes, la polla se cancela automáticamente y el valor de la inscripción se reintegra al saldo de recargas del usuario.
{% endhint %}
{% endstep %}

{% step %}
#### **Registrar pronósticos**

Ingrese sus predicciones para los eventos definidos en la polla.
{% endstep %}
{% endstepper %}

#### **Condiciones:**

* La inscripción solo está disponible antes del inicio del primer partido.
* Una vez inscrito, no es posible retirarse de la polla.
* Los pronósticos pueden registrarse o modificarse hasta 1 minuto antes del inicio del primer evento.
* Una vez iniciado un partido, no se permiten cambios.
* Los pronósticos de otros participantes permanecen ocultos hasta el inicio del evento.

***

### 6. Resultados y premios

Al finalizar la polla, el sistema procesa automáticamente los resultados, calcula los puntajes, genera el ranking de participantes y la distribución de los premios correspondientes.

{% stepper %}
{% step %}
#### Cálculo de puntuación

El sistema toma los resultados oficiales de los partidos (_considerando únicamente los 90 minutos reglamentarios, sin incluir tiempos extra ni penales_) y evalúa los pronósticos de cada usuario.

El puntaje se asigna según la precisión del pronóstico, teniendo en cuenta:

* Resultado exacto del partido
* Equipo ganador
* Cantidad de goles
* Otros eventos definidos en la configuración

A mayor precisión, mayor será el puntaje obtenido.
{% endstep %}

{% step %}
#### Generación del ranking

Con base en los puntajes obtenidos, el sistema organiza automáticamente a los participantes en una tabla de posiciones.

* Los usuarios se ordenan de mayor a menor puntaje.
* El ranking puede visualizarse durante y al finalizar la polla.

En caso de empate:

* Se prioriza el mayor número de aciertos exactos.
* Si el empate persiste, el premio se distribuye proporcionalmente entre los empatados o se define por sorteo en caso de premios físicos.
{% endstep %}

{% step %}
#### Distribución de premios

Una vez definido el ranking final, los premios se asignan según la posición obtenida.

El pozo total corresponde a la suma de las inscripciones de los participantes; la plataforma retiene un porcentaje como comisión y el valor restante se distribuye entre los tres jugadores con mayor puntaje en el ranking.
{% endstep %}
{% endstepper %}

***

### 7. **Validaciones y Reglas de Negocio**

* La polla puede ser **cancelada** si no alcanza el mínimo de 4 participantes al momento de iniciar; en este caso, el valor de inscripción se reintegra automáticamente al saldo de recargas del usuario. Esta condición aplica únicamente para pollas privadas.
* El sistema descuenta automáticamente el valor de inscripción del saldo disponible al unirse a una polla.
* El sistema acredita automáticamente los premios obtenidos al finalizar la polla, según la posición en el ranking.
* El sistema reintegra automáticamente el valor de inscripción en caso de cancelación, abonándolo al saldo de recargas del usuario.
* El saldo del usuario se actualiza en tiempo real después de cada operación.
* Todas las transacciones de los usuarios (_débito, crédito y reintegro_) se registran en el [historial de movimientos](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/jugadores/reportes-seccion-jugadores/historial-de-movimientos) para su consulta.
* El reporte de las pollas deportivas se visualiza desde [Reporte de pollas deportivas](https://app.gitbook.com/s/UadX6RX6l8fMhEZxOqcT/manual-de-usuario-backoffice/reportes/reporte-de-pollas-deportivas) en el Backoffice.

***

### **8. Control de Versiones**

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th>Versión</th><th>Fecha</th><th width="151.1666259765625">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>11/03/2026</td><td>David velasquez</td><td>Documento inicial</td></tr></tbody></table>

</details>
