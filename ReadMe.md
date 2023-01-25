# <h1 align=center> **PROYECTO INDIVIDUAL No. 2**
#  <h1 align=center>**Datathon**  <h1>

En este proyecto se pusieron a prueba nuestros conocimientos en el campo de la predicción de datos. Clasificando los precios de propiedades utilizando una base da datos ya dada utulizando aprendizaje supervisado con el modelo de regresión logistica ya que este es utilizado para clasificación binaria

<br>
#### Analisis Exploratorio de los Datos (EDA)
**id**: (int) Identificador del anuncio
**region**: (str) Región de USA donde se encuentra la propiedad
**region_url**: (str) Link web del anuncio
**price**: (int) Precio de la propiedad
**type**: (str) Tipo de propiedad 
**sqfeet**: (int) Metros cuadrados de la propiedad
**beds**: (int) Cantidad de habitaciones
**baths**: (int) Cantidad de baños
**cats_allowed**: (int) Si se permiten gatos en la propiedad (1=sí, 0=no)
**dogs_allowed**: (int) Si se permiten perro en la propiedad (1=sí, 0=no)
**smooking_allowed**: (int) Si se permite fumar en la propiedad (1=sí, 0=no)
**wheelchair_access**: (int) Si la propiedad tiene acceso para sillas de ruedas (1=sí, 0=no)
**electric_vehicle_charge**: (int) Si la propiedad posee punto de carga para vehículos electricos (1=sí, 0=no)
**comes_furnished**: (int) Si la propiedad está amoblada (1=sí, 0=no)
**laundry_options**: (str) Opciones de lavandería
**parking_options**: (str) Opciones de parqueadero
**image_url**: (str) Link web de la imagen de la propiedad
**description**: (str) Descripción de la propiedad puesta en el anuncio
**lat**: (float) Latitud
**long**: (float) Longitud
**state**: (str) Código del estado al que pertenece la propiedad
<br>

El proyeto fue dividido en dos partes: una parte de transformación y una de predicción
<br>

#### 1. TRANSFORMACION

Se importaron las librerías necesarias
Se cargan los archivos
Se evaluó la información de los datasets
Se graficaron los puntos en el mapa
Se graficaron algunas variables numéricas
Se verificaron y transformaron los valores nulos
Se creó la columna Category_price
Se realizó el proceso labelEncoding para algunas columnas
Se realizó una tabla de correlación 
Se realizó una grafica para revisar las correlaciones
<br>

#### 2. PREDICCIÓN

Se instancia el modelo de regresión logística
Se entrena el modelo
Hacemos la predicción
Calculamos Accuracy y Recall

Finalmente guardamos nuestro archivo de predicción generado
