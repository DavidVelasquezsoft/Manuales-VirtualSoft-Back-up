---
description: >-
  Este repositorio almacena los reportes mensuales de depósitos realizados por
  los usuarios de Doradobet Perú.
---

# Repositorio regulación Doradobet Perú.

### **1. Acceso al Módulo**

**Ruta de Acceso**: FileZilla > home > regulaciondoradobetperu > reports > regulacion > depositos

***

### **2. Funcionalidades**

**📂 2.1 Generación Automática de Reportes**

El sistema genera automáticamente un reporte cada mes

**🛡️ 2.2 Control de Acceso**

Solo los usuarios autorizados con acceso al servidor podrán ingresar al repositorio.

***

### **3. Contenido del Reporte**

<table><thead><tr><th width="232.8887939453125">Columna</th><th>Descripción</th></tr></thead><tbody><tr><td><code>Partner</code></td><td>Partner en el cual se realizó el depósito</td></tr><tr><td><code>Pais</code></td><td>País del partner en el que el usuario realizó el depósito.</td></tr><tr><td><code>ID</code></td><td>Identificador único del depósito.</td></tr><tr><td><code>ID Usuario</code></td><td>ID del usuario que realizó el depósito.</td></tr><tr><td><code>Nombre</code></td><td>Nombre del usuario que realizó el depósito.</td></tr><tr><td><code>Correo</code></td><td>Correo del usuario que realizó el depósito.</td></tr><tr><td><code>DNI</code></td><td>Documento de identidad del usuario que realizó el depósito.</td></tr><tr><td><code>Fecha de Creación</code></td><td>Fecha en la que se generó el depósito.</td></tr><tr><td><code>Proveedor</code></td><td>Proveedor por el cual se realizó el depósito.</td></tr><tr><td><code>Nombre Sistema Pasarela Pago</code></td><td>Pasarela de pago utilizada para realizar el depósito.</td></tr><tr><td><code>Tipo</code></td><td>Tipo de depósito realizado.</td></tr><tr><td><code>Moneda</code></td><td>Moneda utilizada para hacer el depósito.</td></tr><tr><td><code>Valor</code></td><td>Monto total por el cual se realizó el depósito.</td></tr><tr><td><code>Comisión</code></td><td>Monto de comisión correspondiente al referente que vinculó al usuario.</td></tr><tr><td><code>Impuesto Deposito</code></td><td>Impuesto cobrado por el depósito</td></tr><tr><td><code>Modificado</code></td><td>Fecha en la que se modificó el depósito.</td></tr><tr><td><code>Estado</code></td><td>Estado en el que se encuentra el depósito.</td></tr><tr><td><code>Notas</code></td><td>Notas adicionales generadas al momento de hacer el depósito.</td></tr><tr><td><code>External ID</code></td><td>Código externo que referencia el depósito.</td></tr><tr><td><code>IP</code></td><td>IP desde la cual se realizó el depósito.</td></tr><tr><td><code>Recepción de Efectivo</code></td><td>Monto recibido en efectivo al momento de hacer el depósito.</td></tr></tbody></table>

***

### **4. Validaciones y Reglas de Negocio**

* El archivo se genera el primero de cada mes, guardándose automáticamente con el siguiente nombre: **DepositosRegulacionPeru\_mes\_año.csv**
* El archivo siempre se genera el formato .[CSV](https://app.gitbook.com/u/QNLawjQjAmOHwajEjd48cer1Xpq2)

***

### **5. Control de Versiones**

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 22-09-2025 | Ronald Peláez | Documento inicial  |
