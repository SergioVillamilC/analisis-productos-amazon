# analisis-productos-amazon
Se analiza una base de datos de kaggle, contiene una descripción de los diferentes productos en amazon; el análisis se hace mendiante el uso de Python, para la limpieza de datos, creación de base de datos para las sentencias usadas de SQL y contiene un dashboard interctivo de Power BI.

## __Contenido del Repositorio__

* __Código__: Contiene el código de Python.
  * `Analisis_priductos_amazon.ipynb`: Script para la limpieza de datos, creación de la base de datos, sentencias de SQL y generación de visualizaciones.
  * `requirements.txt`: Versión de bibliotecas necesarias para compilar el archivo de Python.

* __Dashboard__: Archivo `.pbix` del dashboard de Power BI.
  * `proyect_amazon.pbix`: Dashboard interactivo con análisis visual de varias relaciones.

* __Datos__: Contiene los datos utilizados en el proyecto.
  
  * `amazon_categories.csv`: Datos crudos descargados de __Kaggle__, contiene la relación entre el nombre y el id de las categorias del documento `amazon_products.csv`
 
  * `amazon_products.csv`: Datos crudos descargados de __Kaggle__.
* `Análisis_productos_amazon.pdf`: Contiene un reporte del proyecto con todo el análisis que se realizó tanto en Power BI como en Python.

## __Dashboard __
El archivo `proyect_amazon.pbix` de Power Bi incluye:

* __Aporte de las categorías al precio total__
* __Precio total de los productos y los productos vendidos en el último mes por categoría__
* __Precio total de los productos y total de reviews por categoría__
* __Precio total de los productos según su calificación de estrellas__
* __Segmentadores de datos__ para las categorías, calificación, compras último mes, bestseller
*__Tarjeta Total precio de productos__ 

## __Cómo usar este Proyecto__

1. __Explorar el Dashboard__:
  * Descarga el archivo `proyect_amazon.pbix` y ábrelo en Power Bi Desktop.
2.  __Reproducir el análisis con Python__:
  * Usa el archivo de Python `Analisis_productos_amazon.ipynb` para procesar los datos paso a paso y generar visualizaciones. Es necesario descargar también los archivos contenidos en la carpeta de Data para poder usar en el script de Python.
3. __Leer el reporte__:
  * Descargar el archivo `Análisis_amazon_productos.pdf`, que contiene una síntesis de todo el análisis realizado, juntando resultados de Power BI y Python.


## __Contribuciones__
Todas las contribuciones son bien recibidas. Si tienes alguna sugerencia, mejora o detectas un error, no dudes en enviar un pull request.


