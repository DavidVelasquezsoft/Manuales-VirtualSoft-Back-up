---
description: >-
  El Informe de Agentes proporciona una visión detallada del desempeño de los
  agentes en la plataforma. Permite filtrar y consultar información clave
  relacionada con las apuestas, premios y ganancias
---

# Informe de Agentes

> **¿Qué es un Agente?**
>
> Un **Agente** corresponde a una persona natural o jurídica autorizada para operar un punto de venta de apuestas y ofrecer los servicios de la plataforma a los clientes finales. Los agentes actúan como intermediarios entre la empresa y los usuarios, registrando las apuestas realizadas desde establecimientos autorizados.

***

### 1. Acceso al Módulo

**Ruta de Acceso:** Agentes > Informe de agentes

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (237).png" alt=""><figcaption><p>Figura#1: Captura de pantalla sección informe de agentes.</p></figcaption></figure>

***

### 3. Acciones disponibles

<table><thead><tr><th width="130">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtros</strong></td><td>Establece los criterios que utilizará el sistema para consultar la información de los agentes.</td></tr><tr><td><strong>Limpiar</strong></td><td>Restablece todos los filtros de búsqueda a su estado inicial.</td></tr><tr><td><strong>Consultar</strong></td><td>Ejecuta la consulta utilizando los filtros seleccionados y presenta los resultados encontrados.</td></tr></tbody></table>

***

### 4. Filtros

<table><thead><tr><th width="129">Campo</th><th width="126">Tipo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Rango de fechas</td><td>Permite seleccionar el período que será utilizado para realizar la consulta.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra la información según el país donde opera el agente.</td></tr><tr><td><strong><code>Tipo de Apuesta</code></strong></td><td>Lista desplegable</td><td>Consulta un tipo específico de apuesta <em>(Apuestas Creadas, Apuestas Cerradas o Apuestas Pagadas).</em></td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo numérico</td><td>Permite buscar un agente mediante su identificador único dentro de la plataforma.</td></tr><tr><td><strong><code>Nombre</code></strong></td><td>Campo de texto</td><td>Busca un agente utilizando el nombre registrado en el sistema.</td></tr><tr><td><strong><code>Login</code></strong></td><td>Campo de texto</td><td>Busca un agente mediante el nombre de usuario con el que accede a la plataforma.</td></tr></tbody></table>

***

### 5. Resultados de consulta

Al hacer clic en **Consultar**, el sistema mostrará los registros que cumplan con los filtros seleccionados.

{% hint style="warning" %}
**Nota:**\
Los resultados mostrados corresponden únicamente al período definido en el filtro **Fecha** y a los criterios de búsqueda seleccionados.
{% endhint %}

<table><thead><tr><th width="171">Campo</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>País</code></strong></td><td>País donde opera el agente.</td></tr><tr><td><strong><code>Afiliador</code></strong></td><td>Usuario responsable de la afiliación del agente a la red comercial.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Identificador único asignado al agente dentro de la plataforma.</td></tr><tr><td><strong><code>Usuario</code></strong></td><td>Nombre de usuario utilizado por el agente para acceder al sistema.</td></tr><tr><td><strong><code>Fecha</code></strong></td><td>Fecha correspondiente a la información registrada.</td></tr><tr><td><strong><code>Moneda</code></strong></td><td>Moneda utilizada para las apuestas realizadas.</td></tr><tr><td><strong><code>Cantidad Tickets</code></strong></td><td>Número total de apuestas registradas durante el período consultado.</td></tr><tr><td><strong><code>Valor Apostado</code></strong></td><td>Valor total apostado por los clientes atendidos por el agente.</td></tr><tr><td><strong><code>Stake Promedio</code></strong></td><td>Valor promedio apostado por cada ticket registrado.</td></tr><tr><td><strong><code>Valor Premios</code></strong></td><td>Valor total pagado en premios durante el período consultado.</td></tr><tr><td><strong><code>Bonos</code></strong></td><td>Valor total de los bonos otorgados durante el período consultado.</td></tr><tr><td><strong><code>GGR</code></strong></td><td>Gross Gaming Revenue (Ingreso Bruto del Juego), calculado como la diferencia entre el valor apostado y el valor de los premios pagados.</td></tr><tr><td><strong><code>GGR %</code></strong></td><td>Porcentaje del GGR respecto al valor total apostado.</td></tr></tbody></table>

***

### 6. Validaciones y reglas del negocio

* El filtro **Fecha** es obligatorio para ejecutar la consulta.
* El sistema únicamente mostrará información correspondiente al período seleccionado.
* Si no existen registros para los filtros ingresados, la tabla de resultados no mostrará información.
* El valor del **Stake Promedio** corresponde al promedio del valor apostado por cada ticket registrado.
* El **GGR** se calcula como la diferencia entre el valor total apostado y el valor total de premios pagados.
* El **GGR %** representa el porcentaje del GGR respecto al valor total apostado.
* La información presentada dependerá de los permisos asignados al usuario autenticado.

***

### 7. Control de Versiones

<details>

<summary>🔽 Historial de versiones</summary>

<table><thead><tr><th width="103">Versión</th><th width="132">Fecha</th><th width="127">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>24/07/2026</td><td>Karol Navia</td><td>Reestructuración del manual.</td></tr></tbody></table>

</details>
