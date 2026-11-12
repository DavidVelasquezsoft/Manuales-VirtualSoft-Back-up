# Repositorio Fullcarga Doradobet-Ecuador

El Repositorio **Reportes Fullcarga Doradobet Ecuador** es un espacio seguro en el que diariamente se almacenan los reportes de **Recargas** y **Retiros** correspondientes a la operación en Ecuador.

### **1. Acceso al Módulo**

**Ruta de Acceso**: FileZilla > Reports > Reportes Fullcarga Doradobet Ecuador&#x20;

***

### **2. Funcionalidades**

**📂 2.1 Generación Automática de Reportes**

El sistema genera automáticamente dos archivos separados cada día.

* **fullcarga\_recargas / fullcarga\_recargas\_{YYYYMMDD}.csv**
* **fullcarga\_retiros / fullcarga\_retiros\_{YYYYMMDD}.csv**

Los archivos se generan y se almacenan automáticamente en el repositorio, dentro de su carpeta correspondiente, sin necesidad de intervención manual.

**🛡️ 2.2 Control de Acceso**

Solo los usuarios autorizados con acceso al servidor podrán ingresar al repositorio.

***

### **3. Contenido de los Reportes**

**3.1 Reporte de Recargas**

El archivo **fullcarga\_recargas\_{YYYYMMDD}.csv** contiene las siguientes columnas en este orden:

<table><thead><tr><th width="296.22216796875">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><code>USERNAME</code></td><td>Nombre de la pasarela de pago.</td></tr><tr><td><code>ID</code></td><td>ID de la recarga.</td></tr><tr><td><code>ID USUARIO</code></td><td>ID del usuario que realizó la recarga.</td></tr><tr><td><code>FECHA DE CREACIÓN</code></td><td>Fecha de creación de la recarga.</td></tr><tr><td><p><code>NOMBRE DEL SISTEMA</code> </p><p><code>PASARELA DE PAGO</code></p></td><td>Pasarela de pago utilizada.</td></tr><tr><td><code>TIPO</code></td><td>Tipo de transacción.</td></tr><tr><td><code>MONEDA</code></td><td>Moneda en la que se registró la recarga.</td></tr><tr><td><code>VALOR</code></td><td>Monto de la recarga.</td></tr><tr><td><code>FECHA MODIFICADO</code></td><td>Última fecha de modificación.</td></tr><tr><td><code>ESTADO</code></td><td>Estado de la transacción.</td></tr><tr><td><code>EXTERNAL ID</code></td><td>Identificador externo de la recarga.</td></tr><tr><td><p><code>NÚMERO DE</code> </p><p><code>TRANSACCIONES</code></p></td><td>Número total de transacciones.</td></tr><tr><td><code>PAIS</code></td><td>País para el cual se realizó la recarga.</td></tr><tr><td><code>PARTNER</code></td><td>Partner para el cual se realizó la recarga.</td></tr></tbody></table>

**3.2 Reporte de Retiros**

El archivo **fullcarga\_retiros\_{YYYYMMDD}.csv** contiene las siguientes columnas en este orden:

<table><thead><tr><th width="256.22222900390625">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><code>PUNTO DE VENTA</code></td><td>Punto de venta asociado al retiro.</td></tr><tr><td><code>ID</code></td><td>ID del retiro.</td></tr><tr><td><code>ID CLIENTE</code></td><td>ID del usuario que realizó el retiro.</td></tr><tr><td><code>VALOR</code></td><td>Monto del retiro.</td></tr><tr><td><code>ESTADO</code></td><td>Estado de la transacción.</td></tr><tr><td><code>FECHA CREACIÓN</code></td><td>Fecha de creación de la transacción.</td></tr><tr><td><code>FECHA PAGADO</code></td><td>Fecha en la que se pagó el retiro.</td></tr><tr><td><code>NÚMERO DE TRANSACCIONES</code></td><td>Número total de transacciones.</td></tr><tr><td><code>PAÍS</code></td><td>País en el que se realizó el retiro.</td></tr><tr><td><code>PARTNER</code></td><td>Partner en el que se realizó el retiro.</td></tr></tbody></table>

***

### **4. Validaciones y Reglas de Negocio**

* Los reportes se generan **automáticamente todos los días** a la hora configurada (por defecto 02:00 a.m.).
* Ambos archivos (**Recargas** y **Retiros**) deben almacenarse en el mismo repositorio.
* El nombre de los archivos debe cumplir exactamente con el formato definido:
  * `fullcarga_recargas_{YYYYMMDD}.csv`
  * `fullcarga_retiros_{YYYYMMDD}.csv`

***

### **5. Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 01-09-2025 | Ronald Peláez | Documento inicial  |
