---
description: >-
  En este reporte encontrarás información general sobre casino, es un archivo
  que podrás generar de manera automática.
---

# Evolución del análisis y reporte de casino

Aquí encontrarás un paso a paso en el que se explicará el uso y como generar este archivo de manera automática.

**Requerimientos**: Para realizar este proceso se necesita previamente tener instalado lo siguiente:

* **Librerías**: Las librerías importadas necesitan estar previamente instaladas.

{% hint style="warning" %}
Nota: En caso de no tener instaladas las librerías, se puede hacer con el comando "pip install nombre\_libreria".
{% endhint %}

* **Python**: Se debe tener instalada la versión 3.10.16 en la máquina donde se ejecute el notebook.

### Orden para ejecutar las celdas (se deben ejecutar cada una en este orden).

Este proceso se realiza por medio de una ejecución en notebook de Python, cada bloque de código indicado en este manual es una celda en la interfaz del aplicativo, en cada celda se encuentra un botón "**RUN (▶️)**" en la parte superior izquierda, se debe seleccionar este botón para ejecutar cada una de las celdas.

{% hint style="warning" %}
**Nota**: para ir a cada bloque de código referenciado, selecciona el nombre en el listado.
{% endhint %}

1. [#librerias](evolucion-del-analisis-y-reporte-de-casino.md#librerias "mention")
2. [#constantes-y-configuracion](evolucion-del-analisis-y-reporte-de-casino.md#constantes-y-configuracion "mention")
3. [#funciones](evolucion-del-analisis-y-reporte-de-casino.md#funciones "mention")
4. [#seleccionando-sql-adecuada-basado-en-los-datos-ingresados-por-el-usuario](evolucion-del-analisis-y-reporte-de-casino.md#seleccionando-sql-adecuada-basado-en-los-datos-ingresados-por-el-usuario "mention")\
   \
   Al ejecutar esta celda se le pedirán al usuario los siguientes datos:&#x20;

* Fecha inicio: Fecha de inicio para el obtener los datos del reporte.
* Fecha fin: Fecha final en la que se obtendrán los datos del reporte.
* Mandante: ID del partner para la consulta.
* País: ID del país para la consulta.
* Hora inicio y hora fin: Hora que se utilizará para realizar la consulta en la base de datos.

{% hint style="warning" %}
**Nota**: Los parámetros de la hora no son obligatorios y se pueden omitir, por defecto se toma hora inicio = 00:00:00 y fecha fin = 23:59:59.
{% endhint %}

Los demás parámetros mencionados **SÍ** deben ser introducidos en el formato indicado. De lo contrario, aparecerá un mensaje diciendo que los parámetros son obligatorios.

5. [#tarjetas-kpis](evolucion-del-analisis-y-reporte-de-casino.md#tarjetas-kpis "mention")
6. [#graficas](evolucion-del-analisis-y-reporte-de-casino.md#graficas "mention")
   1. [#apuestas-y-ggr-en-el-tiempo](evolucion-del-analisis-y-reporte-de-casino.md#apuestas-y-ggr-en-el-tiempo "mention")
   2. [#top-subproviders](evolucion-del-analisis-y-reporte-de-casino.md#top-subproviders "mention")
   3. [#top-players](evolucion-del-analisis-y-reporte-de-casino.md#top-players "mention")
7.  [#generacion-de-html](evolucion-del-analisis-y-reporte-de-casino.md#generacion-de-html "mention")\
    \
    Esta celda genera un reporte HTML con imágenes generadas para el reporte por las celdas "KPIs, Gráficas, Top Subproviders, Top players"


8.  [#generacion-reporte-en-pdf](evolucion-del-analisis-y-reporte-de-casino.md#generacion-reporte-en-pdf "mention")\
    \
    Esta celda genera el archivo PDF con el reporte de casino, este archivo se guarda en la carpeta report con el nombre "report.pdf", la cual se encuentra en la carpeta donde el notebook se está ejecutando.<br>

    <figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption><p>figura #1: Captura de pantalla carpeta reports.</p></figcaption></figure>

### Librerías:&#x20;

```python
from sqlalchemy import create_engine
import matplotlib.ticker as ticker
import matplotlib.pyplot as plt
from weasyprint import HTML
import seaborn as sns
import pandas as pd
import numpy as np
import datetime
import os
```

[#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden](evolucion-del-analisis-y-reporte-de-casino.md#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden "mention") click aquí para regresar al listado.

### Constantes y configuración:

```python
FORMAT_DATE = "%Y-%m-%d"

TODAY = datetime.datetime.now()
TODAY_STR = datetime.datetime.now().strftime(FORMAT_DATE)
HORA_INCIO = '00:00:00'
HORA_FIN = '23:59:59'

HTML_PATH = os.path.join(os.getenv('BASE_PATH'), 'test_report.html')
PDF_PATH = os.path.join(os.getenv('BASE_PATH'), 'reports/report.pdf')

from matplotlib import font_manager

font_dirs = [r"fonts"]  # The path to the custom font file.
font_files = font_manager.findSystemFonts(fontpaths=font_dirs)

for font_file in font_files:
    font_manager.fontManager.addfont(font_file)

plt.rcParams['font.family'] = 'Poppins'

MONTH_TO_MES = {
    'January': 'Enero',
    'February': 'Febrero',
    'March': 'Marzo',
    'April': 'Abril',
    'May': 'Mayo',
    'June': 'Junio',
    'July': 'Julio',
    'August': 'Agosto',
    'September': 'Septiembre',
    'October': 'Octubre',
    'November': 'Noviembre',
    'December': 'Diciembre',
}

WEEKDAY_NAME = {
    0: 'Lunes',
    1: 'Martes',
    2: 'Miércoles',
    3: 'Jueves',
    4: 'Viernes',
    5: 'Sábado',
    6: 'Domingo'
}

PARTNERS = {
    '0': 'Doradobet',
    '8': 'Ecuabet',
    '23': 'Paniplay',
    '18': 'Gangabet',
    '21': 'Camanbet',
    '27': 'Ganaplay'
}

PAISES = {
    '2': 'Nicaragua',
    '46': 'Chile',
    '60': 'Costa Rica',
    '66': 'Ecuador',
    '68': 'El Salvador',
    '94': 'Guatemala',
    '102': 'Honduras',
    '173': 'Perú',
    '232': 'Venezuela VES',
    '243': 'Venezuela USD'
}


COLORS = {
    'Black': '#000000',
    'Davys Greys': '#4C4C4C',
    'Granite grey': '#646464',
    'Silver': '#C9C9C9',
    'Azul Oscuro': '#16697A',
    'Azul claro': '#E4F1Fc'
}

PARTNER_DETAILS = {}
```

[#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden](evolucion-del-analisis-y-reporte-de-casino.md#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden "mention") click aquí para regresar al listado.

### Funciones:&#x20;

```python
def get_user_input():

    use_summary_query = False

    START_DATE = input("Ingrese fecha incio de consulta (YYYY-MM-DD): ")
    END_DATE = input("Ingrese fecha fin de consulta (YYYY-MM-DD): ")
    MANDANTES = input("Ingrese mandantes separados por coma (0, 8): ")
    PAISES = input("Ingrese países separados por coma (0, 8): ")

    if not START_DATE or not END_DATE or not MANDANTES or not PAISES:
        print("Todos los campos son obligatorios. Por favor, inténtelo de nuevo.")
        return {}
    
    START_TIME = input("Ingrese hora inicio de consulta (HH:MM:SS) o presione enter si la hora es 00:00:00 : ")
    END_TIME = input("Ingrese hora fin de consulta (HH:MM:SS) o presione enter si la hora es 23:59:59 : ")

    START_TIME = START_TIME if START_TIME else '00:00:00'
    END_TIME = END_TIME if END_TIME else '23:59:59'

    # if datetime.datetime.strptime(END_DATE, '%Y-%m-%d').day < TODAY.day and START_TIME == '00:00:00' and END_TIME == '23:59:59':
    #     use_summary_query = True

    if abs((TODAY - datetime.datetime.strptime(END_DATE, FORMAT_DATE)).days) > 0 and START_TIME == '00:00:00' and END_TIME == '23:59:59':
        use_summary_query = True

    return {
        'start_date': START_DATE,
        'end_date': END_DATE,
        'mandantes': MANDANTES,
        'paises': PAISES,
        'start_time': START_TIME,
        'end_time': END_TIME,
        'use_summary_query': use_summary_query
    }
    
def get_query(summary_query):

    casino_query = ""
    bonos_query = ""

    if summary_query:
        with open('sql/casino_resumen.sql', 'r') as file:
            casino_query = file.read()
    else:
        with open('sql/casino_transaccional.sql', 'r') as file:
            casino_query = file.read()
    
    with open('sql/bonos_casino.sql', 'r') as file:
        bonos_query = file.read()
    
    return casino_query, bonos_query       

def query_db(sql):

    result = {}

    engine = create_engine(os.getenv('SNOWFLAKE_URL'))
    
    try:
        with engine.connect() as connection:
            df = pd.read_sql(sql, connection)
            result['data'] = df
            result['error'] = False
            result['error_name'] = ''
            result['error_info'] = ''
    except Exception as e:

        result['data'] = pd.DataFrame()
        result['error'] = True
        result['error_name'] = type(e).__name__
        result['error_info'] = e

    return result

def format_number(num, precision=2):

    parts = []

    if precision != 0:
        parts = f"{round(num, precision)}".split('.')
    else:
        parts = f"{round(num)}".split('.')

    decimal_part = ''
    int_part = ''

    if len(parts) > 1:
        decimal_part = parts[-1]
    int_part = f"{int(parts[0]):,.0f}".replace(',', '.')

    if decimal_part:
        return f"{int_part},{decimal_part}"
    else:
        return f"{int_part}"


sql_trms = ""
df_trms = pd.DataFrame()
with open('sql/trms.sql', 'r') as f:
    sql_trms = f.read()

result_trms = query_db(sql_trms)
if not result_trms['error']:
    print("Consulta TRMs ejecutada correctamente.")
    df_trms = result_trms['data']
    df_trms['Partner-Pais'] = df_trms['nombre'] + "-" + df_trms['pais_nom']
else:
    print(f"Error al ejecutar la consulta de TRMs: {result_trms['error_name']}")
    print(f"Información del error: {result_trms['error_info']}")

df_trms.head()

partners = df_trms['Partner-Pais'].unique().tolist()

for partner in partners:

    if partner not in PARTNER_DETAILS.keys():
        df_temp = df_trms[df_trms['Partner-Pais']==partner].copy()
        mandante = df_temp['nombre'].values[0]
        pais = df_temp['pais_nom'].values[0]
        moneda = df_temp['moneda'].values[0]
        iso = df_temp['iso'].values[0]
        trm = df_temp['trm_usd'].values[0]

        PARTNER_DETAILS[partner] = {
            'mandante':mandante,
            'pais':pais,
            'moneda':moneda,
            'iso': iso,
            'trm_usd': trm

        }

```

[#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden](evolucion-del-analisis-y-reporte-de-casino.md#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden "mention") click aquí para regresar al listado.

### Seleccionando SQL adecuada basado en los datos ingresados por el usuario:

```python
opciones_periodo = ('Mes Pasado', 'Mes actual', 'Ayer', 'Personalizado')
user_input = get_user_input()
casino_query = ""
bonos_query = ""
if not user_input:
    print("No se proporcionaron datos válidos. Saliendo del programa.")
else:
    if user_input['use_summary_query']:
        casino_query, bonos_query = get_query(summary_query=True)
    else:
        casino_query, bonos_query = get_query(summary_query=False)
        casino_query = casino_query.replace('{HORA_INICIO}', user_input['start_time'])
        casino_query = casino_query.replace('{HORA_FIN}', user_input['end_time'])

    casino_query = casino_query.replace('{FECHA_INICIO}', user_input['start_date'])
    casino_query = casino_query.replace('{FECHA_FIN}', user_input['end_date'])
    casino_query = casino_query.replace('{MANDANTES}', user_input['mandantes'])
    casino_query = casino_query.replace('{PAISES}', user_input['paises'])

    bonos_query = bonos_query.replace('{FECHA_INICIO}', user_input['start_date'])
    bonos_query = bonos_query.replace('{FECHA_FIN}', user_input['end_date'])
    bonos_query = bonos_query.replace('{MANDANTES}', user_input['mandantes'])
    bonos_query = bonos_query.replace('{PAISES}', user_input['paises'])
    bonos_query = bonos_query.replace('{HORA_INICIO}', user_input['start_time'])
    bonos_query = bonos_query.replace('{HORA_FIN}', user_input['end_time'])

data = pd.DataFrame()
result = query_db(casino_query)
mapping_bonos = dict()

if not result['error']:
    print("Consulta apuestas casino ejecutada correctamente.")
    data = result['data']
    if not data.empty:
        result_bonos = query_db(bonos_query)
        if not result_bonos['error']:
            print("Consulta bonos casino ejecutada correctamente.")
            data_bonos = result_bonos['data']
            if not data_bonos.empty:
                data_bonos_diario = data_bonos.groupby(by=['partner', 'pais', 'fecha']).agg({
                    'bonos_casino': 'sum'
                }).reset_index()
                mapping_bonos = dict(zip(data_bonos_diario['fecha'], data_bonos_diario['bonos_casino']))
            else:
                print("No se encontró data de bonos en el período consultado.")
        else:
            print(f"Error al ejecutar la consulta de bonos: {result_bonos['error_name']}")
            print(f"Información del error: {result_bonos['error_info']}")

        data.columns = [colname.title().replace('_', ' ') for colname in data.columns]
        data.rename(columns = {
            'Id Usuario': 'ID Usuario',
            'Id Mandante': 'ID Partner',
            'Id Pais': 'ID Pais',
            'Tipocasino': 'Tipo Casino'
        }, inplace=True)
        data['Bonos Casino'] = 0

        if mapping_bonos:
            data['Bonos Casino'] = data['Fecha'].drop_duplicates(keep='first').map(mapping_bonos)
            data['Bonos Casino'] = data['Bonos Casino'].fillna(0)
        
        data['Partner-Pais'] = data['Partner'] + "-" + data['Pais']
        
        data['Fecha'] = pd.to_datetime(data['Fecha'], format=FORMAT_DATE)
    else:
        print("No se encontró data de apuestas en el período consultado.")
else:
    print(f"Error al ejecutar la consulta: {result['error_name']}")
    print(f"Información del error: {result['error_info']}")

```

[#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden](evolucion-del-analisis-y-reporte-de-casino.md#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden "mention") click aquí para regresar al listado.

### Tarjetas KPIs:

```python
unique_games = data['Juego'].unique().size
print(f"Cantidad juegos únicos: {format_number(unique_games)}")

unique_users = data['ID Usuario'].unique().size
print(f"Cantidad usuarios únicos: {format_number(unique_users)}")

cantidad_spin_total = data['Cantidad Spin'].sum()
print(f"Cantidad total de spin: {format_number(cantidad_spin_total, precision=0)}")

apuesta_total = data['Apuesta Casino'].sum()
print(f"Valor total apostado: {format_number(apuesta_total, precision=0)}")

premios_total = data['Premio Casino'].sum()
print(f"Valor total premios: {format_number(premios_total, precision=0)}")

premios_bonos = data['Premio Bono'].sum()
print(f"Valor total premios bonos: {format_number(premios_bonos, precision=0)}")

bonos_casino = data['Bonos Casino'].sum()
print(f"Valor total bonos casino: {format_number(bonos_casino, precision=0)}")

GGR_sin_bonos = apuesta_total - premios_total - premios_bonos
GGR_con_bonos = apuesta_total - premios_total - premios_bonos - bonos_casino

print(f"GGR (sin bonos): {format_number(GGR_sin_bonos, precision=0)}")
print(f"GGR (con bonos): {format_number(GGR_con_bonos, precision=0)}")

percentage_GGR = (GGR_con_bonos / apuesta_total)*100
print(f"%GGR: {format_number(percentage_GGR, precision=2)}")

```

[#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden](evolucion-del-analisis-y-reporte-de-casino.md#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden "mention") click aquí para regresar al listado.

### Gráficas:

Las siguientes celdas de código son para generar gráficas e imagenes para el reporte.

#### Apuestas y GGR en el tiempo:

```python
df_bets = data.groupby(['Partner', 'Pais', 'Fecha']).agg({
    'Apuesta Casino': 'sum',
    'Premio Casino': 'sum',
    'Premio Bono': 'sum',
    'Bonos Casino': 'sum'
}).reset_index()

df_bets['GGR'] = df_bets['Apuesta Casino'] - df_bets['Premio Casino'] - df_bets['Premio Bono'] - df_bets['Bonos Casino'] 
df_bets['GGR (sin bonos)'] = df_bets['Apuesta Casino'] - df_bets['Premio Casino'] - df_bets['Premio Bono'] 

df_bets.set_index('Fecha', inplace=True)
fig, ax = plt.subplots(nrows=2, ncols=1, figsize=(15, 8), sharex=True)

df_bets[['Apuesta Casino']].plot(marker='o', ms=8, color='#16697A', lw=2, label='Valor Apuestas', ax=ax[0])
ax[0].set_title('Apuestas diarias')

ax[0].ticklabel_format(style='plain', axis='y')
ax[0].yaxis.set_major_formatter(ticker.FuncFormatter(format_number))
ax[0].set_axisbelow(True)
ax[0].grid(visible=True, linestyle='--', linewidth=1, alpha=0.6)
ax[0].legend(loc='best')

df_bets[['GGR']].plot(marker='o', ms=8, color='#16697A', lw=2, label='GGR', ax=ax[1])
df_bets[['GGR (sin bonos)']].plot(marker='o', ms=8, color='#000', lw=2, label='GGR (sin bonos)', ax=ax[1])
ax[1].set_title('GGR diario')
ax[1].ticklabel_format(style='plain', axis='y')
ax[1].yaxis.set_major_formatter(ticker.FuncFormatter(format_number))
ax[1].set_axisbelow(True)
ax[1].grid(visible=True, linestyle='--', linewidth=1, alpha=0.6)
ax[1].legend(loc='best')

plt.savefig('figures/ggr&bets_over_time.svg')

plt.show()
```

[#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden](evolucion-del-analisis-y-reporte-de-casino.md#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden "mention") click aquí para regresar al listado.

#### Top subproveedores:

```python
df_proveedor = data.groupby(by=['Proveedor', 'Subproveedor', 'Partner', 'Pais']).agg({
    'ID Usuario': 'nunique',
    'Apuesta Casino': 'sum',
    'Premio Casino': 'sum',
    'Cantidad Spin': 'sum'
}).reset_index()
df_proveedor.rename(columns={'ID Usuario': 'Cantidad Jugadores'}, inplace=True)
df_proveedor.sort_values(by='Apuesta Casino', ascending=False, inplace=True)
df_proveedor = df_proveedor[['Subproveedor', 'Apuesta Casino', 'Premio Casino', 'Cantidad Spin', 'Cantidad Jugadores']][:5].copy()

# Top games
df_juegos = data.groupby(by=['Proveedor', 'Subproveedor', 'Partner', 'Pais', 'Juego']).agg({
    'ID Usuario': 'nunique',
    'Apuesta Casino': 'sum',
    'Premio Casino': 'sum',
    'Cantidad Spin': 'sum'
}).reset_index()
df_juegos.rename(columns={'ID Usuario': 'Cantidad Jugadores'}, inplace=True)
df_juegos.sort_values(by='Apuesta Casino', ascending=False, inplace=True)
df_juegos = df_juegos[['Juego', 'Apuesta Casino', 'Premio Casino', 'Cantidad Spin', 'Cantidad Jugadores']][:5].copy()
fig, ax = plt.subplots(nrows=1, ncols=2, figsize=(15, 6))
x = np.arange(len(df_proveedor['Subproveedor']))
width = 0.25
ax[0].set_title('Top 5 subproveedores por apuesta casino')
ax[0].bar(x-width, df_proveedor['Cantidad Spin'], width, label='Cantidad Spin', color='#000')
ax[0].bar(x, df_proveedor['Apuesta Casino'], width, label='Valor Apostado ($)',  color='#16697A')
ax[0].bar(x+width, df_proveedor['Premio Casino'], width, label='Valor Premios ($)', color='gray')
ax[0].set_xticks(x)
subrpoviders_names = [name.replace(' ', '\n', 1) for name in df_proveedor['Subproveedor'].values]
ax[0].set_xticklabels(subrpoviders_names, rotation=0, ha='center', fontsize=10)
ax[0].ticklabel_format(style='plain', axis='y')
ax[0].yaxis.set_major_formatter(ticker.FuncFormatter(format_number))
ax[0].set_axisbelow(True)
ax[0].grid(visible=True, linestyle='--', linewidth=1, alpha=0.6)
ax[0].legend(loc='upper right')


x = np.arange(len(df_juegos['Juego']))
ax[1].set_title('Top 5 juegos por apuesta Casino')
ax[1].bar(x-width, df_juegos['Cantidad Spin'], width, label='Cantidad Spin', color='#000')
ax[1].bar(x, df_juegos['Apuesta Casino'], width, label='Valor Apostado ($)',  color='#16697A')
ax[1].bar(x+width, df_juegos['Premio Casino'], width, label='Valor Premios ($)', color='gray')


ax[1].set_xticks(x)
games_names = [name.replace(' ', '\n', 2) for name in df_juegos['Juego'].values]
ax[1].set_xticklabels(games_names, rotation=0, ha='center', fontsize=10)
ax[1].ticklabel_format(style='plain', axis='y')
ax[1].yaxis.set_major_formatter(ticker.FuncFormatter(format_number))
ax[1].set_axisbelow(True)
ax[1].grid(visible=True, linestyle='--', linewidth=1, alpha=0.6)
ax[1].legend(loc='upper right')


plt.savefig('figures/barcharts_topsub&games.svg')

plt.show()
```

[#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden](evolucion-del-analisis-y-reporte-de-casino.md#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden "mention") click aquí para regresar al listado.

#### **Apuestas por día de semana:**

```python
data['Weekday'] = data['Fecha'].dt.weekday
data['Weekdayname'] = data['Weekday'].map(WEEKDAY_NAME)
bets_weekday = data.groupby(by=['Partner', 'Pais', 'Weekday', 'Weekdayname']).agg({
    'ID Usuario': 'nunique',
    'Cantidad Spin': 'sum',
    'Apuesta Casino': 'sum',
    'Premio Casino': 'sum'
}).reset_index()

bets_weekday.rename(columns={'ID Usuario': 'Cantidad Jugadores'}, inplace=True)

casino_type_bets = data.groupby(by=['Partner', 'Pais', 'Tipo Casino']).agg({
    'ID Usuario': 'nunique',
    'Cantidad Spin': 'sum',
    'Apuesta Casino': 'sum',
    'Premio Casino': 'sum'
}).reset_index()

casino_type_bets.rename(columns={'ID Usuario': 'Cantidad Jugadores'}, inplace=True)

fig, ax = plt.subplots(nrows=1, ncols=1, figsize=(15, 4))
x = np.arange(len(bets_weekday['Weekdayname']))
width = 0.35

ax.set_title('Apuestas por día de semana')
ax.bar(x-width/2, bets_weekday['Apuesta Casino'], width, label='Apuesta Casino ($)', color='#16697A')
ax.bar(x+width/2, bets_weekday['Premio Casino'], width, label='Valor Premios ($)', color='gray')
ax.set_xticks(x)
ax.set_xticklabels(bets_weekday['Weekdayname'], rotation=0, ha='center', fontsize=10)
ax.ticklabel_format(style='plain', axis='y')
ax.yaxis.set_major_formatter(ticker.FuncFormatter(format_number))
ax.set_axisbelow(True)
ax.grid(visible=True, linestyle='--', linewidth=1, alpha=0.6)
ax.legend(loc='best')

plt.savefig('figures/weekdays_bets.svg')

plt.show()
```

#### Top jugadores:

```python
df_players = data.groupby(by=['ID Usuario', 'Partner', 'Pais']).agg({
    'Apuesta Casino': 'sum',
    'Cantidad Spin': 'sum',
    'Premio Casino': 'sum',
    'Premio Bono': 'sum',
    'Bonos Casino': 'sum'
}).reset_index()
df_players.sort_values(by='Apuesta Casino', ascending=False, inplace=True)
df_players['GGR'] = df_players['Apuesta Casino'] - df_players['Premio Casino'] - df_players['Premio Bono'] - df_players['Bonos Casino']
df_players['GGR (sin bonos)'] = df_players['Apuesta Casino'] - df_players['Premio Casino'] - df_players['Premio Bono']
df_players = df_players[:5].copy()
fig, ax = plt.subplots(nrows=1, ncols=2, figsize=(15, 6))
x = np.arange(len(df_players['ID Usuario']))
width = 0.35
ax[0].set_title('Top 5 jugadores por apuesta casino')
ax[0].bar(x-width/2, df_players['Apuesta Casino'], width, label='Valor Apostado ($)',  color='#16697A')
ax[0].bar(x+width/2, df_players['Premio Casino'], width, label='Valor Premios ($)', color='gray')
ax[0].set_xticks(x)
ax[0].set_xticklabels(df_players['ID Usuario'], rotation=0, ha='center', fontsize=10)
ax[0].ticklabel_format(style='plain', axis='y')
ax[0].yaxis.set_major_formatter(ticker.FuncFormatter(format_number))
ax[0].set_axisbelow(True)
ax[0].grid(visible=True, linestyle='--', linewidth=1, alpha=0.6)
ax[0].legend(loc='best')


ax[1].set_title('GGR Top 5 jugadores')
ax[1].bar(x-width/2, df_players['GGR'], width, label='GGR ($)',  color='#4C4C4C')
ax[1].bar(x+width/2, df_players['GGR (sin bonos)'], width, label='GGR sin bonos ($)', color='#646464')
ax[1].set_xticks(x)
ax[1].set_xticklabels(df_players['ID Usuario'], rotation=0, ha='center', fontsize=10)
ax[1].ticklabel_format(style='plain', axis='y')
ax[1].yaxis.set_major_formatter(ticker.FuncFormatter(format_number))
ax[1].set_axisbelow(True)
ax[1].grid(visible=True, linestyle='--', linewidth=1, alpha=0.6)
ax[1].legend(loc='best')

plt.savefig('figures/barcharts_topsplayers.svg')

plt.show()
```

[#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden](evolucion-del-analisis-y-reporte-de-casino.md#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden "mention") click aquí para regresar al listado.

### Generación de HTML:

```python
html_head = ""
html_foot = ""
assets_folder = os.path.join(os.getenv('BASE_PATH'), 'assets')
with open(os.path.join(assets_folder, 'head.html'), 'r') as f:
    html_head = f.read()

with open(os.path.join(assets_folder, 'foot.html'), 'r') as f:
    html_foot = f.read()

kpis = {
    'unique_games': (unique_games, 'number', 'Juegos únicos'),
    'unique_players': (unique_users, 'number', 'Usuarios únicos'),
    'spin': (cantidad_spin_total, 'number', 'Total spin'),
    'bets': (apuesta_total, 'currency', 'Total apuestas'),
    'prizes': (premios_total, 'currency', 'Total Premios'),
    'bonus_prizes': (premios_bonos, 'currency', 'Total premios bonos'),
    'bonus': (bonos_casino, 'currency', 'Bonos casino'),
    'ggr2': (GGR_sin_bonos, 'currency', 'GGR (sin bonos)'),
    'ggr': (GGR_con_bonos, 'currency', 'GGR (con bonos)'),
    r'%ggr': (percentage_GGR, 'percentage', r'%GGR')
}

figures_report = {

    'ggr&bets_over_time': {
        'format': 'svg',
        'description': 'valor apuestas y GGR en el tiempo',
        'class': 'ggrbets-over-time',
        'order': 1
    },
    'weekdays_bets': {
        'format': 'svg',
        'description': 'valor apuestas de acuerdo al día de la semana',
        'class': 'bets_per_weekday',
        'order': 2
    },
    'barcharts_topsub&games': {
        'format': 'svg',
        'description': 'valor apuestas en el tiempo',
        'class': 'barcharts-topsubgames',
        'order': 3
    },
    'barcharts_topsplayers': {
        'format': 'svg',
        'description': 'Top apuestas usuarios',
        'class': 'barcharts_topsplayers',
        'order': 4
    }
}

for partner in data['Partner-Pais'].unique().tolist():


    fecha_inicio = datetime.datetime.strptime(user_input['start_date'], FORMAT_DATE)
    fecha_fin = datetime.datetime.strptime(user_input['end_date'], FORMAT_DATE)

    mes_inicio_EN = fecha_inicio.strftime("%B")
    mes_inicio_ES = MONTH_TO_MES[mes_inicio_EN]
    dia_inicio = fecha_inicio.strftime("%d")
    dia_inicio = f"{int(dia_inicio)}" if int(dia_inicio)<10 else dia_inicio

    mes_fin_EN = fecha_inicio.strftime("%B")
    mes_fin_ES = MONTH_TO_MES[mes_fin_EN]
    dia_fin = fecha_fin.strftime("%d")
    dia_fin = f"{int(dia_fin)}" if int(dia_fin)<10 else dia_fin

    partner_name = PARTNER_DETAILS[partner]['mandante']
    country_name = PARTNER_DETAILS[partner]['pais']
    iso_code = PARTNER_DETAILS[partner]['iso']


    html_main = f"""
    <main>
        <div class="partner">
            <img class="flag" src="assets/flags/{iso_code}.png" alt="Bandera país">
            <p><span>Partner: </span>{partner_name}</p>
            <p><span>País: </span>{country_name}</p>
            <p><span>Período de estudio: </span>{mes_inicio_ES} {dia_inicio} - {mes_fin_ES} {dia_fin}</p>
        </div>
        <div class="kpis">
    """


    for kpi_detail in kpis.values():

        valor = kpi_detail[0]
        label = kpi_detail[2]
        if kpi_detail[1]=='currency':
            valor = format_number(valor)
            valor = f"&#36;{valor}"
        elif kpi_detail[1]=='percentage':
            valor = format_number(valor, precision=4)
            valor = f"{valor}&#37;"
        else:
            valor = f"{format_number(valor)}"


        html_main += f"""
        <div class="kpis-card">
            <p class="kpis-card_value">{valor}</p>
            <p class="kpis-card_label">{label}</p>
        </div>

        """

    html_main += "</div>" 

    for figure_name, figure_details in figures_report.items():
        html_main += f"""<img class="{figure_details['class']}" src="figures/{figure_name}.{figure_details['format']}" alt="{figure_details['description']}">"""

    html = html_head + html_main + html_foot

    with open('test_report.html', 'w') as f:
        f.write(html)
```

[#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden](evolucion-del-analisis-y-reporte-de-casino.md#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden "mention") click aquí para regresar al listado.

### Generación Reporte en PDF:

```python
with open(HTML_PATH, 'r') as f:
    HTML(string=f.read(), base_url=os.getenv('BASE_PATH')).write_pdf(PDF_PATH)
```

[#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden](evolucion-del-analisis-y-reporte-de-casino.md#orden-para-ejecutar-las-celdas-se-deben-ejecutar-cada-una-en-este-orden "mention") click aquí para regresar al listado.
