---
description: >-
  Permite consultar información clave relacionada con los pagos realizados a
  usuarios por concepto de comisiones. Este reporte es esencial para el control,
  seguimiento y análisis de las comisiones.
---

# Pagar comisiones

### 1. Acceso al Módulo

**Ruta de Acceso**: BackOffice > Menú principal > Reportes > Pagar Comisiones

***

### 2. Visualización

<figure><img src="../../.gitbook/assets/image (35).png" alt=""><figcaption><p>Figura #1: Captura de pantalla filtros de búsqueda.</p></figcaption></figure>

***

### 3. Funcionalidades

<table><thead><tr><th width="163">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td><strong>Filtrar comisiones</strong></td><td>Permite aplicar filtros de búsqueda por usuario, país, tipo de comisión, tipo de usuario o estado del pago.</td></tr><tr><td><strong>Visualizar tabla de resultados</strong></td><td>Presenta la información de las comisiones pagadas o pendientes según los filtros aplicados.</td></tr><tr><td><strong>Exportar los resultados</strong></td><td>Exporta en formato Excel la tabla de los resultados según los filtros seleccionados.</td></tr></tbody></table>

**🔎 3.1 Filtros principales**

<table><thead><tr><th width="123">Campo</th><th width="155">Tipo de Control</th><th width="484">Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha</code></strong></td><td>Calendario</td><td>Selecciona un rango de fechas para filtrar las comisiones pagadas en un periodo específico.</td></tr><tr><td><strong><code>ID Usuario</code></strong></td><td>Campo de texto</td><td>Identificador único del usuario al que corresponde el pago de las comisiones.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Permite filtrar las comisiones según el país asociado al usuario.</td></tr><tr><td><strong><code>Pago de Comisiones</code></strong></td><td>Lista desplegable</td><td>Filtra los resultados según el estado del pago <em>(pagado, pendiente, rechazado).</em></td></tr><tr><td><strong><code>Tipo de Comisión</code></strong></td><td>Lista desplegable</td><td>Especifica el tipo de comisión que se desea consultar.</td></tr><tr><td><strong><code>Tipo de Usuario</code></strong></td><td>Lista desplegable</td><td>Define el perfil del usuario <em>(Concesionario, Subconcesionario, Punto de Venta, Afiliado).</em></td></tr><tr><td><strong><code>ID Concesionario</code></strong></td><td>Campo de texto</td><td>Identificador del concesionario relacionado con el usuario.</td></tr><tr><td><strong><code>Visualización Resumida</code></strong></td><td>Casilla de verificación</td><td>Activa una vista simplificada del reporte para mostrar únicamente los totales y datos relevantes.</td></tr></tbody></table>

**📊 Tabla de Resultados**\
Los resultados de la consulta se presentan en una tabla con las siguientes columnas:

<table><thead><tr><th width="183">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><img src="../../.gitbook/assets/credit_card.png" alt="" data-size="line"></td><td>Despliega un pop-up con la validación para pagar las comisiones seleccionadas.</td></tr><tr><td><strong>Seleccionar</strong></td><td>Selecciona las comisiones para poder realizar el pago de dichas comisiones.</td></tr><tr><td><strong>ID Usuario</strong></td><td>Identificador único del usuario al que corresponde el pago de las comisiones.</td></tr><tr><td><strong>Nombre Usuario</strong></td><td>Nombre del usuario que recibió o está relacionado con el pago de comisiones.</td></tr><tr><td><strong>Tipo de Usuario</strong></td><td>Perfil del usuario <em>(Concesionario, Subconcesionario, Punto de Venta, Afiliado).</em></td></tr><tr><td><strong>Pago de Comisiones</strong></td><td>Estado del pago de comisiones <em>(pagado, pendiente, rechazado).</em></td></tr><tr><td><strong>Estado</strong></td><td>Indica el estado general del pago <em>(activo, inactivo, etc.).</em></td></tr><tr><td><strong>Total</strong></td><td>Monto total pagado o correspondiente a las comisiones dentro del rango consultado.</td></tr></tbody></table>

***

### **4. Validaciones y Reglas de Negocio**

* No es obligatorio completar todos los filtros para realizar una búsqueda.
* La información mostrada dependerá de los filtros seleccionados en la consulta.
* Los montos reflejados corresponden al rango de fechas y condiciones aplicadas en los filtros.

***

### **5. Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 21/10/2025 | Ronald Peláez | Documento inicial  |
