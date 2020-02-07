<img alt="mastergis" src="https://user-images.githubusercontent.com/16768318/73984100-c96ee500-492f-11ea-92a8-87ba3ffc1a60.jpg" align="right" width = 15%/>

# **Introducción a Google Earth Engine con Python**

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![lifecycle](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://www.tidyverse.org/lifecycle/#stable)

### **Introducción**

La manipulación de ciento de Gigabytes (incluso Terabytes) de datos espaciales, ha sido una actividad muy limitada debido al alto costo de adquisición de la infraestructura computacional adecuada y a la falta de personal calificado en ingeniería de datos. Google Earth Engine (GEE) ha solucionado este problema ofreciendo una plataforma completamente gratuita, fácil de usar y con la capacidad de procesar cientos de Gigabytes datos (raster y vector) en cuestión de minutos.

En Este curso presentamos el potencial que tiene el uso de Google Earth Engine para reemplazar los flujos de trabajos tradicionales en procesamiento digital de imágenes. Todos los tópicos y ejemplos tocados serán abordados con problemas reales ligados al quehacer diario de un profesional en teledetección y SIG. Para poder llevar este curso satisfactoriamente es necesario conocimientos de programación en Python y teledetección básica.

### **¿Qué vas a lograr en este curso?**

1) Mostrar las ventajas y desventajas entre flujos de trabajo tradicionales (ej: ENVI + ARCGIS) frente a Google Earth Engine (Lazy evaluation).

2) Mostrar las ventajas y desventajas entre usar GEE con Python vs JavaScript.

3) Dar a conocer a los participantes la forma adecuada de trabajar con sistemas cliente-servidor.

4) Introducir a los participantes en la sintaxis de Google Earth Engine con Python.

5) Poder descargar, manipular y procesar cientos de imágenes satelitales (Sentinel, Landsat, Modis, etc.) de cualquier parte del mundo en cuestión de minutos.

### **Silabus**

- **Modulo 01:** Entendiendo GEE
  - Bienvenidos
  - ¿Qué es Google Earth Engine?
  - Catálogo de datos de GEE
  - ¿Comó funciona la Infraestructura computacional de GEE?
  - API’s: Programación funcional
  - Cuáles son las ventajas y desventajas de usar el API de Python frente al de JavaScript.
  - Colab (jupyter notebbok) como interfaz para usar Python.
  - [Primeros pasos en colab y comandos básicos en Linux](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module01/01_introcolab.ipynb).


- **Modulo 2:** Sintaxis de mínima de Python para GEE
  - [Tipos de datos en Python](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/01_tipodedatos.ipynb).
  - [Estructuras de datos](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/02_estructuradedatos.ipynb).
  - [Operadores de comparación](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/03_Operadoresdecomparación.ipynb).
  - [Declaraciones if, else y elif](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/04_if_else_elif.ipynb)
  - [Ciclos for](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/05_Ciclosfor.ipynb).
  - [Funciones](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/06_Funciones.ipynb).
  - [Expresiones lambda y funciones map y filter](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/07_Lambda.ipynb).
  - [modulos y paquetes en Python](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module02/08_Modulos_y_Paquetes.ipynb).
  
  
- **Modulo 3:** Datos Espaciales en Python
  - [WKT y GeoJSON e introducción a geopandas](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module03/01_wkt_geojson.ipynb).
  - Subida de datos raster y vector a GEE


- **Modulo 4:** Sintaxis en GEE 
  - [Como inicializar la Earth Engine Python API](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module04/01_EDGEE.ipynb).
  - [ED básicas en Google Earth Engine](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module04/01_EDGEE.ipynb).
  - [ED espaciales en Google Earth Engine I (ee.Image): cálculo de índices: NDVI, NDWI.](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module04/02_EDGEE.ipynb) 
  - [ED espaciales en Google Earth Engine II ( ee.ImageCollection): map y filter](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module04/03_EDGEE.ipynb)
  - [ED espaciales en Google Earth Engine III (ee.Feature y ee.FeatureCollection).](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module04/04_EDGEE.ipynb)


- **Modulo 5:** GEE en acción I
  - [Manipulación de ee.Image y ee.ImageCollection y exploración de metadatos](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module05/01_metadatos_I.ipynb).
  - [Manipulación de ee.Feature y ee.FeatureCollection y exploración de metadatos](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module05/02_metadatos_II.ipynb).
  - [Reducciones espacio temporales en ee.Image y ee.ImageCollection.](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module05/03_reducer.ipynb)
  - [Ejercicio 01:  Generación de una base de datos espacial](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module05/04_Ejercicio_01.ipynb).
  - [Ejercicio 02:  Descarga automática de imágenes Sentinel-2 en cualquier parte del mundo de forma 100% automatica.](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module05/05_Ejercicio_02.ipynb)


- **Modulo 6:** GEE en acción II
  - [Composición y mosaico](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module06/01_composites.ipynb).
  - [Técnicas de visualización en ee.Image.Collection](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module06/02_ICviz.ipynb)
  - [Clasificacion supervisada y no supervisada.](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module06/03_class.ipynb)
  - [Ejercicio:  Predicción de la erosión hídrica a nivel mundial](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module06/04_RUSLE.ipynb).
  - [Ejercicio Propuesto:  Estimación de la Precipitación máxima en 24 horas y evapotranspiración para todos las distritos de Loreto - Perú](https://colab.research.google.com/github/csaybar/EarthEngineMasterGIS/blob/master/module06/prop01_PP_ETP.ipynb).


### Instructor

**Cesar Luis Aybar Camacho**

Ingeniero geógrafo con experiencia en análisis geo estadístico, modelamiento hidrológico, sistema de información geográfica y teledetección. Dominio de los lenguajes de programación C++, R y Python, además de conceptos ligados a la hidrología satelital, machine learning y web scraping. 


### **Changelog**

```
Version 0.0.1
 - Acentos y caracteres extraños eliminados.
 - 6 modulos y 2 ejercicios propuestos.
 - Libros y informacion extra.
```
