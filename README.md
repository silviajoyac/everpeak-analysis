EverPeak Retail Analysis – Sprint 6
Este repositorio contiene el análisis de datos realizado durante el Sprint 6 del caso EverPeak Retail.
El proyecto utiliza el dataset everpeak_retail, que contiene información de transacciones de clientes y permite analizar diferentes aspectos del comportamiento de compra, como precios, cantidades, edades de clientes, ciudades, categorías de productos y métodos de pago.
El dataset fue diseñado para representar datos reales de retail, incluyendo problemas de calidad como valores faltantes y valores atípicos, con el objetivo de practicar procesos de limpieza, exploración y análisis de datos.

 Contenido del repositorio
El repositorio contiene principalmente:
* everpeak_analysis.ipynb → Notebook principal donde se desarrolla el análisis de los datos.
* README.md → Documento con la descripción del proyecto y las instrucciones para utilizar el notebook.

 Cómo abrir el notebook en Google Colab
Para trabajar con el notebook en Google Colab:
1. Abre el archivo everpeak_analysis.ipynb.
2. Selecciona la opción Open in Colab.
3. Una vez abierto en Colab, ejecuta las celdas del notebook en orden.
También puedes abrirlo directamente desde Google Colab si tienes disponible el enlace al archivo.

 Cómo reproducir el análisis
1. Abre everpeak_analysis.ipynb.
2. Ejecuta las celdas en orden.
3. Verifica que el dataset esté disponible en la ubicación indicada dentro del notebook.
4. Revisa las tablas, gráficos y resultados generados.
El análisis utiliza principalmente Python y las siguientes librerías:
* pandas para la manipulación y análisis de datos.
* numpy para operaciones numéricas y segmentación.
* matplotlib para visualizaciones.
* seaborn para gráficos estadísticos.

 Objetivo del análisis
El objetivo del proyecto es explorar los datos de EverPeak Retail para comprender el comportamiento de las transacciones y detectar problemas que puedan afectar el análisis.
Durante el proyecto se trabajan los siguientes aspectos:
* Exploración y revisión de los datos.
* Análisis de variables numéricas y categóricas.
* Distribución de precios.
* Distribución de edades de los clientes.
* Análisis de cantidades compradas.
* Análisis del valor de los pedidos.
* Identificación de posibles valores atípicos.
* Comparación de métodos de detección de outliers mediante IQR y Z-Score.
* Segmentación de clientes según volumen de compra.
* Segmentación según edad y volumen de compra.
* Segmentación según método de pago y volumen de compra.

Análisis realizado
El notebook incluye diferentes ejercicios y análisis para explorar el comportamiento de los datos.
Entre ellos se encuentran:
* Histogramas de price y customer_age.
* Boxplots de quantity y order_value.
* Análisis de valores atípicos.
* Cálculo de promedio, mediana y desviación estándar.
* Segmentación mediante if-else, np.where() y apply().
* Análisis de categorías como Fashion, Sports y Toys.
* Análisis de métodos de pago y volumen de compra.

 Conclusiones
El análisis permite obtener una visión general de la distribución de los datos de EverPeak Retail, identificar posibles valores atípicos y explorar diferentes segmentos de clientes.
Las conclusiones específicas y los resultados obtenidos se encuentran dentro del notebook everpeak_analysis.ipynb.
