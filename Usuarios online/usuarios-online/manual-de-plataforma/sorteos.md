---
description: >-
  Permite a los usuarios participar en dinámicas para ganar premios como bonos,
  giros gratis o dinero en efectivo. Cada sorteo tiene condiciones específicas.
---

# Sorteos

### Configuración general

### 1. Acceso al Módulo:

**Ruta de Acceso**: Plataforma usuarios online > Menú principal > Sorteos

***

### **2. Acciones del Usuario**

<table><thead><tr><th width="267.22222900390625">Elemento</th><th width="136.7777099609375">Acción</th><th>Descripción</th></tr></thead><tbody><tr><td>Filtro por tipo de sorteo</td><td>Seleccionar</td><td>Permite elegir entre todos los sorteos registrados o el estado del sorteo.</td></tr><tr><td>Botón “Participa Ahora”</td><td>Click</td><td>Inscribe al usuario en el sorteo correspondiente si cumple los requisitos.</td></tr><tr><td>Botones “Camino” y “Stickers”</td><td>Click</td><td>Permite el acceso a información del proceso de acumulación o elementos coleccionables del sorteo.</td></tr></tbody></table>

***

#### 2.1. Otras configuraciones

<table><thead><tr><th width="125.88885498046875">Campo</th><th width="113.66668701171875">Tipo de control</th><th>Descripción</th><th>Observaciones</th></tr></thead><tbody><tr><td><strong>Contador de tiempo</strong></td><td>Visual dinámica</td><td>Muestra el tiempo restante para que finalice el sorteo.</td><td>Se actualiza en tiempo real.</td></tr><tr><td><strong>Requisitos para participar</strong></td><td>Texto informativo</td><td>Informa al usuario si debe apostar o depositar una cantidad mínima.</td><td>Puede variar según el tipo de sorteo.</td></tr><tr><td><strong>Premios del sorteo</strong></td><td>Visual en tarjetas</td><td>Presenta una descripción gráfica del premio (bonos, dinero, giros gratis).</td><td>Puede incluir imágenes o íconos.</td></tr><tr><td><strong>Usuarios inscritos</strong></td><td>Visual dinámica</td><td>Visualiza la cantidad de usuarios inscritos en el sorteo</td><td>Se actualiza la información cada 120 segundos.</td></tr></tbody></table>

***

### 3. Validaciones y Reglas de Negocio

* Solo se puede participar en un sorteo si se cumplen los requisitos de acumulación.
* Cada sorteo tiene una fecha y hora límite.
* Los usuarios no pueden registrarse en sorteos inactivos o finalizados.
* El botón “Participa ahora” solo estará habilitado si el usuario cumple condiciones de elegibilidad.

***

### 4. Control de Versiones

<details>

<summary>🕛Historial de versiones</summary>

| Versión | Fecha      | Autor         | Cambios Realizados                    |
| ------- | ---------- | ------------- | ------------------------------------- |
| 1.0     | 21/07/2025 | Karol Navia   | Creación inicial del módulo Sorteos   |
| 1.1     | 09/09/2025 | Ronald Peláez | Nuevo contador de usuarios inscritos. |

</details>
