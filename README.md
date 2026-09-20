# EverPeak Retail Analysis – Sprint 6

Este repositorio contiene el análisis de datos realizado durante el Sprint 6 del caso EverPeak Retail.
El proyecto utiliza el dataset everpeak_retail, que contiene información sobre transacciones de clientes y permite analizar diferentes aspectos del comportamiento de compra, como precios, cantidades, edades de los clientes, ciudades, categorías de productos y métodos de pago.
El dataset incluye problemas de calidad de datos, como valores faltantes y valores atípicos, con el objetivo de practicar procesos de exploración, limpieza y análisis de datos.

## Contenido del repositorio
El repositorio contiene los siguientes archivos:
* everpeak_analysis.ipynb Notebook principal donde se desarrolla el análisis de los datos durante el Sprint 6.
* README.md Documento que describe el proyecto y explica cómo utilizar el notebook.

## Cómo abrir el notebook en Google Colab
Para trabajar con el notebook en Google Colab:
1. Abre el repositorio en GitHub.
2. Abre el archivo everpeak_analysis.ipynb.
3. Selecciona la opción Open in Colab o Open with Colab.
4. Una vez abierto en Colab, ejecuta las celdas del notebook en orden.
También puedes abrir el notebook directamente desde Google Colab si tienes disponible el enlace correspondiente.

## Cómo reproducir el análisis
Para reproducir el análisis:
1. Abre everpeak_analysis.ipynb.
2. Verifica que el dataset esté disponible en la ubicación indicada dentro del notebook.
3. Ejecuta las celdas en orden.
4. Revisa las tablas, visualizaciones y resultados generados.
El análisis utiliza principalmente Python y las siguientes librerías:
* pandas para la manipulación y el análisis de datos.
* numpy para operaciones numéricas y segmentación.
* matplotlib para la creación de visualizaciones.
* seaborn para gráficos estadísticos.

## Objetivo del análisis
El objetivo principal del proyecto es aplicar técnicas de análisis exploratorio de datos para comprender el comportamiento de las transacciones de EverPeak Retail y detectar problemas que puedan afectar la interpretación de los resultados.
Entre los objetivos específicos se encuentran:
* Explorar y revisar la estructura de los datos.
* Analizar variables numéricas y categóricas.
* Analizar la distribución de precios y edades de los clientes.
* Analizar las cantidades compradas y el valor de los pedidos.
* Identificar posibles valores atípicos.
* Comparar métodos de detección de outliers mediante IQR y Z-Score.
* Analizar diferentes categorías de productos.
* Explorar la distribución de clientes por ciudad.
* Segmentar clientes según su volumen de compra.
* Analizar patrones relacionados con los métodos de pago.

## Principales análisis realizados
**Distribución de precios**
Se analiza la variable price mediante un histograma para comprender la distribución de los precios y observar posibles valores extremos.
Distribución de edades
Se utiliza la variable customer_age para analizar la distribución de las edades de los clientes.
**Cantidad comprada** 
Se analiza la variable quantity mediante boxplots para observar su distribución y detectar posibles valores atípicos.
**Valor de los pedidos**
La variable order_value se analiza mediante boxplots para observar la distribución del gasto de los clientes en diferentes categorías de productos.
**Detección de outliers**
Se utilizan dos métodos estadísticos para identificar posibles valores atípicos:
* IQR (Rango Intercuartílico).
* Z-Score.
Esto permite comparar los registros identificados como posibles valores atípicos mediante diferentes criterios.
**Segmentación de clientes**
Se desarrollan diferentes reglas de segmentación utilizando:
* Volumen de compra.
* Edad del cliente.
* Método de pago.
* Combinaciones entre estas variables.
Estas segmentaciones permiten explorar diferentes perfiles de clientes dentro del dataset.

## Conclusiones
El análisis permite explorar la distribución y calidad de los datos de EverPeak Retail, identificar posibles valores atípicos y analizar diferentes características del comportamiento de los clientes.
Los resultados y conclusiones específicas obtenidos durante el análisis se encuentran documentados dentro del notebook everpeak_analysis.ipynb.
