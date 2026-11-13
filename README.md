# Proyecto ConnectaTel: Análisis de datos y segmentación de clientes
**Objetivo del proyecto**

El objetivo de este proyecto es analizar el comportamiento de los clientes de la empresa de telecomunicaciones ConnectaTel en México y Colombia, con el propósito de identificar patrones de consumo, detectar valores atípicos y segmentar a los usuarios según su edad y nivel de uso de los servicios.

A partir de los resultados, se busca generar insights y recomendaciones comerciales que permitan mejorar la oferta de planes, fortalecer la fidelización y desarrollar estrategias de marketing orientadas a las necesidades de cada segmento.
Datasets utilizados

Para desarrollar el análisis se utilizaron tres conjuntos de datos:

*-plans.csv:* contiene información sobre los planes ofrecidos por la empresa.

*-users_latam.csv:* contiene información de los clientes, como identificador, nombre, edad, ciudad, fecha de registro, plan contratado y fecha de cancelación.

*-usage.csv:* contiene los registros de actividad de los usuarios, incluyendo llamadas, mensajes, fechas, duración y longitud de los registros.

(Los datos corresponden al mercado de México y Colombia y contemplan registros hasta el año 2024.)

**Etapas del análisis**

El proyecto se desarrolló mediante las siguientes etapas:

*1. Carga y exploración de datos:* importación de los datasets y revisión de su estructura, dimensiones y tipos de datos.

*2. Identificación de problemas de calidad:* exploración de valores nulos, datos faltantes, valores inválidos y posibles sentinels.

*3. Limpieza y preparación de datos:* revisión de valores inválidos, tratamiento de sentinels y estandarización de columnas de fecha.

*4. Análisis estadístico descriptivo:* cálculo de estadísticas para comprender las características de los usuarios y su comportamiento de consumo.

*5. Visualización y detección de outliers:* elaboración de histogramas y diagramas de caja (boxplots) para analizar distribuciones e identificar valores atípicos mediante el método IQR.

*6. Segmentación de clientes:* clasificación de los usuarios según su nivel de uso (bajo, medio y alto) y grupo de edad (joven, adulto y adulto mayor).

*7. Insights y recomendaciones comerciales:* interpretación de los resultados y formulación de propuestas para mejorar los planes y las estrategias de fidelización de ConnectaTel.

**Herramientas y librerías**

El análisis se desarrolló utilizando Python y las siguientes librerías:

*Pandas:* manipulación, limpieza y análisis de datos.

*NumPy:* operaciones numéricas.

*Matplotlib:* creación de visualizaciones.

*Seaborn:* elaboración de gráficos estadísticos.

*Jupyter Notebook:* desarrollo y documentación del análisis.

**Cómo ejecutar el notebook**

*El análisis está documentado en un notebook de Jupyter (.ipynb), que contiene el código, las visualizaciones y las interpretaciones de los resultados.*

Para ejecutarlo:

1. Descarga o clona este repositorio de GitHub.

2. Asegúrate de contar con Python y las librerías necesarias.

3. Ubica los tres archivos CSV en la carpeta correspondiente.

4. Abre el archivo .ipynb utilizando Jupyter Notebook, JupyterLab o Google Colab.

5. Ejecuta las celdas en orden, desde el inicio hasta el final.

**Guía de reproducción**

Para reproducir el análisis correctamente:

1. Clona el repositorio o descarga sus archivos.

2. Verifica que los datasets (plans.csv, users_latam.csv y usage.csv) estén disponibles en la ruta indicada en el notebook.

3. Si ejecutas el proyecto fuera del entorno original, actualiza las rutas de lectura de los archivos CSV según su ubicación.

4. Instala las librerías necesarias si aún no están disponibles.

5. Ejecuta todas las celdas del notebook en orden para obtener los resultados, gráficos, segmentaciones e insights.

**Instalación de librerías:**

pip install pandas numpy matplotlib seaborn jupyter

**Resultados esperados**

El análisis permite identificar problemas de calidad en los datos, comprender los patrones de consumo de los clientes, reconocer segmentos según edad y nivel de uso, y detectar comportamientos atípicos.

Finalmente, los hallazgos sirven como base para proponer estrategias comerciales y oportunidades de mejora en los planes de ConnectaTel.
