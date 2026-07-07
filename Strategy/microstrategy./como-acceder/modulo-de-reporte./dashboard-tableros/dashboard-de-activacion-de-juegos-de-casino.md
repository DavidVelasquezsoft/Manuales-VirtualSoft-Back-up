---
description: >-
  El tablero presenta la información consolidada del desempeño de los juegos de
  casino, permitiendo realizar análisis por país, partner, proveedor y
  subproveedor.
---

# Dashboard de activación de juegos de casino

### 1. Acceso al Módulo

**Ruta de Acceso:** Virtualsoft > Informes compartidos > Datas TI > Paneles Visuales

***

### 2. Visualización General

<figure><img src="../../../../.gitbook/assets/image (36) (1).png" alt=""><figcaption><p>Figura#1: Captura de pantalla Dashboard activacion de Juegos de casino.</p></figcaption></figure>

### **🧑‍💻 3. Filtros Disponibles:**

Los filtros permiten ajustar la información visualizada en el tablero, facilitando la segmentación por período, país, partner, proveedor y tipo de casino.

<table><thead><tr><th width="150">Nombre</th><th width="152">Tipo de control</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha de activación</code></strong></td><td>Selector de rango de fechas desde hasta.</td><td>Permite definir el rango de fechas en el que los productos fueron activados al partner.</td></tr><tr><td><strong><code>Fecha casino</code></strong></td><td>Selector de rango de fechas</td><td>Define la fecha en la que inició la operación del juego.</td></tr><tr><td><strong><code>Año de activación</code></strong></td><td>Lista desplegable</td><td>Filtra los registros por año de activación del producto.</td></tr><tr><td><strong><code>Mes de activación</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el mes de activacion del juego.</td></tr><tr><td><strong><code>Semana</code></strong></td><td>Lista desplegable</td><td>Permite filtrar los datos por la semana en la que se realizó la activación del juego.</td></tr><tr><td><strong><code>Partner</code></strong></td><td>Lista desplegable</td><td>Selecciona el partner para realizar su respectivo análisis.</td></tr><tr><td><strong><code>País</code></strong></td><td>Lista desplegable</td><td>Filtra la información por país donde se ejecutan las operaciones.</td></tr><tr><td><strong><code>Proveedor</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el proveedor principal de los juegos de casino.</td></tr><tr><td><strong><code>Subproveedor</code></strong></td><td>Lista desplegable</td><td>Filtra los juegos asociados a un subproveedor específico.</td></tr><tr><td><strong><code>Juego</code></strong></td><td>Lista desplegable</td><td>Permite localizar un juego específico por nombre del producto.</td></tr><tr><td><strong><code>Id producto</code></strong></td><td>Campo de búsqueda</td><td>Busca un producto por su identificador.</td></tr><tr><td><strong><code>Categoría</code></strong></td><td>Lista desplegable</td><td>Filtra los juegos según su categoría o clasificación <em>(por ejemplo: tragamonedas, Slots, Live Casino).</em></td></tr><tr><td><strong><code>Tipo de casino</code></strong></td><td>Lista desplegable</td><td>Permite seleccionar el tipo de casino <em>(Live, Slot o Virtual)</em> para enfocar el análisis.</td></tr></tbody></table>

### 4. Gráficas:

<table><thead><tr><th width="156">Sección</th><th width="122">Tipo de Gráfica</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Gráfico Apuestas vs Premio Casino</code></strong></td><td>Gráfica de líneas</td><td>Muestra la evolución del valor apostado frente al premio entregado durante el período seleccionado.</td></tr><tr><td><strong><code>Gráfico GGR</code></strong></td><td>Gráfica de líneas</td><td>Indica la ganancia bruta del juego <em>(Apuestas - Premios - Bonos Freespins)</em>, permitiendo identificar tendencias de rentabilidad.</td></tr><tr><td><strong><code>Gráfico RTP</code></strong></td><td>Gráfica de líneas</td><td>Representa el porcentaje de retorno al jugador <em>(RTP = [Premio Casino] / [Apuesta Casino])</em>.</td></tr><tr><td><strong><code>Gráfico Cantidad de Giros</code></strong></td><td>Gráfica de líneas</td><td>Refleja el total de giros <em>(spins)</em> generados por semana.</td></tr><tr><td><strong><code>Gráfico Progreso por Operación</code></strong></td><td>Gráfica de barras</td><td>Compara el desempeño por operación o partner, mostrando métricas como valor apostado, GGR y usuarios activos.</td></tr></tbody></table>

***

### 5. Tabla detalle Producto

<table><thead><tr><th width="164">Nombre</th><th>Descripción</th></tr></thead><tbody><tr><td><strong><code>Fecha activación</code></strong></td><td>Fecha en la que el juego fue activado para el partner.</td></tr><tr><td><strong><code>ID producto</code></strong></td><td>Código único que identifica el juego dentro de la plataforma.</td></tr><tr><td><strong><code>Nombre juego</code></strong></td><td>Nombre comercial del juego tal como aparece en la plataforma.</td></tr><tr><td><strong><code>Tipo casino</code></strong></td><td>Clasificación del tipo de casino al que pertenece el juego <em>(Live, Slot o Virtual)</em>.</td></tr><tr><td><strong><code>Categoría</code></strong></td><td>Categoría del juego <em>(por ejemplo: Ruleta, Bingo, Tragamonedas, etc.).</em></td></tr><tr><td><strong><code>Nombre proveedor</code></strong></td><td>Nombre del proveedor principal que ofrece el juego.</td></tr><tr><td><strong><code>Nombre subproveedor</code></strong></td><td>Nombre del subproveedor que opera el juego bajó el proveedor principal.</td></tr><tr><td><strong><code>Estado juego</code></strong></td><td>Indica si el juego se encuentra <em>(A= activo o I=inactivo)</em> en la plataforma.</td></tr><tr><td><strong><code>Estado proveedor</code></strong></td><td>Muestra si el proveedor principal se encuentra <em>(A= activo o I=inactivo)</em>.</td></tr><tr><td><strong><code>Estado subproveedor</code></strong></td><td>Refleja el estado operativo del subproveedor <em>(A= activo o I=inactivo)</em>.</td></tr><tr><td><strong><code>Jugadores únicos</code></strong></td><td>Número total de usuarios diferentes que han jugado el juego dentro del periodo seleccionado.</td></tr><tr><td><strong><code>Spins</code></strong></td><td>Cantidad total de giros o jugadas realizadas en el juego.</td></tr><tr><td><strong><code>Apuesta</code></strong></td><td>Valor total apostado por los jugadores en el juego.</td></tr><tr><td><strong><code>Premios</code></strong></td><td>Valor total pagado en premios a los jugadores.</td></tr><tr><td><strong><code>Premio bono</code></strong></td><td>Valor total de premios entregados por bonos promocionales <em>(Free Spins, etc.).</em></td></tr><tr><td><strong><code>Saldo gratis</code></strong></td><td>Valor de apuestas realizadas con saldo promocional o gratuito.</td></tr><tr><td><strong><code>Apuesta promedio</code></strong></td><td>Promedio del valor apostado por cada jugador o por sesión.</td></tr><tr><td><strong><code>GGR</code></strong></td><td>Ganancia bruta del juego, calculada como Apuesta - Premios - Bonos.</td></tr><tr><td><strong><code>% Margen</code></strong></td><td>Margen de ganancia expresado en porcentaje con respecto al valor apostado.</td></tr><tr><td><strong><code>RTP</code></strong></td><td>Porcentaje de retorno al jugador, calculado como <em>(Premios / Apuesta)</em>.</td></tr></tbody></table>

***

### **🕒 6. Control de Versiones**

<table><thead><tr><th width="105">Versión</th><th width="150">Fecha</th><th width="183">Autor</th><th>Cambios Realizados</th></tr></thead><tbody><tr><td>1.0</td><td>11/11/2025</td><td>Karol Navia</td><td>Documento inicial del tablero Casino por Juegos.</td></tr></tbody></table>
