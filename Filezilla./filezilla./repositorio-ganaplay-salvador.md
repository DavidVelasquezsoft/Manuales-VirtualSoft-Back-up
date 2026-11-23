# REPOSITORIO GANAPLAY SALVADOR

El Repositorio Ganaplay El Salvador es un espacio seguro en el que cada mes se almacena el archivo con la información fiscal del país. Sirve para que el equipo autorizado suba el reporte correspondiente

#### 1. Acceso al Módulo

**Ruta de Acceso**: FileZilla > Servidor Ganaplay El Salvador > reports

***

#### 2. Funcionalidades

**📂 2.1 Carga Mensual del Archivo**

Se sube automáticamente un reporte llamado **“Facturación Ganaplay El Salvador + (Fecha en la que se generó el reporte)”** el primer día de cada mes, con fecha de corte del mes anterior.

**🛡️ 2.2 Control de Acceso**

Solo los usuarios autorizados con acceso al servidor podrán ingresar al repositorio.

***

#### 3. Contenido del Reporte

<table><thead><tr><th width="196.77783203125">Campo</th><th width="144.66668701171875">Tipo de Control</th><th width="209.111083984375">Descripción</th><th width="144.77783203125">Validaciones</th><th>Formato</th></tr></thead><tbody><tr><td><code>Nombre del archivo</code></td><td>Texto</td><td>Debe llamarse <strong>Facturación Ganaplay El Salvador</strong> + (Fecha en la que se generó el reporte)</td><td>Obligatorio y con el nombre exacto.</td><td><a href="https://virtualsoft.gitbook.io/untitled/glosario/#csv">csv</a></td></tr></tbody></table>

**3.1 Contenido del Archivo**

El archivo tiene las siguientes columnas:

| Columna                                                              | Descripción                                                          |
| -------------------------------------------------------------------- | -------------------------------------------------------------------- |
| Periodo                                                              | Mes y año correspondientes al reporte cargado                        |
| [Partner](https://virtualsoft.gitbook.io/untitled/glosario/#partner) | Nombre del socio comercial para el que se generó el reporte          |
| País                                                                 | País al que corresponde la información contenida en el reporte       |
| ID\_Usuario                                                          | ID del usuario que generó el reporte de facturación                  |
| Nombre\_usuario                                                      | Nombre del usuario que generó el reporte de facturación              |
| Tipo\_documento                                                      | Tipo de documento del usuario que generó el reporte                  |
| Número\_documento                                                    | Número de documento del usuario que generó el reporte de facturación |
| [GGR](https://virtualsoft.gitbook.io/untitled/glosario/#ggr)         | Valor del GGR calculado para el periodo indicado                     |

***

#### 4. Validaciones y Reglas de Negocio

* El archivo debe cargarse **únicamente el primer día de cada mes**.
* El nombre del archivo debe ser exactamente **Facturación Ganaplay El Salvador** + (Fecha en la que se generó el reporte).
* El archivo debe tener las columnas indicadas en este manual.

***

#### 5. Control de Versiones

| Versión | Fecha      | Autor         | Cambios Realizados |
| ------- | ---------- | ------------- | ------------------ |
| 1.0     | 2025-13-08 | Ronald Peláez | Documento inicial  |
