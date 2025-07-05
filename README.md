# Análisis Exploratorio de Datos de Viajes en Bicicleta

## Integrantes del equipo

- Edgar Ivan Lozada Sanchez
- Javier Roberto Uribe Sandoval
- Luis Angel Cruz Sotelo
- Perla Citlallin Gutierrez Villanueva
- María Fernanda Rosas García

## Descripción del proyecto

Este proyecto consiste en un análisis exploratorio de un conjunto de datos de viajes en bicicleta compartida. Se realizan transformaciones para limpiar los datos, clasificar variables, crear nuevas columnas útiles y generar visualizaciones para entender patrones en la duración de los viajes, el comportamiento por grupo de edad y género, entre otros aspectos.

## Para ejecutar el notebook

1. **Clona este repositorio o descarga los archivos.**
2. **Instala las librerías necesarias** usando pip:

- import numpy as np
- import pandas as pd
- pd.set_option("display.max_rows", 150)
- import re
- import matplotlib.pyplot as plot
- import cufflinks as cf
- import glob
- import os
- from google.colab import drive
- drive.mount('/content/drive')
- shared_folder_path = "/content/drive/MyDrive/ecobici"
- os.chdir(shared_folder_path)

## imputemos el genero
- from sklearn.impute import SimpleImputer

3. Descarga el archivo csv dentro de la carpeta  en la cual quieres trabajar los datos.
4. Abre y ejecuta el notebook por cada bloque de código para identificar incidencias.

## Conclusiones

- En los histogramas de Hora_retiro y Hora_arribo vemos que se comparten los picos y periodos mas usados, siendo el pico en un periodo de 18:00 a 19:00, el siguiente pico se encuentra en el periodo 08:00 a 09:00, y se tienen un último en el periodo de 14:00 a 16:00
- De acuerdo a grafico de Genero, se observa que el genero Masculino es el que más usa el servicio de Ecobici 
- El rango de edad que usa más este servicio es de 26 a 35 años, siendo un 49.5% de los usuarios 
- En los gráficos correspondiente a fechas (Fecha_Retiro y Fecha_Arribo) , se observa un incremento en los primeros meses del año. Este comportamiento podría estar relacionado con los propósitos que muchas personas adoptan al inicio del año, entre ellos, la de tomar hábitos más saludables como el uso de la bicicleta como medio de transporte.
  
## Graficas generadas

# Notas adicionales
Se usó pandas, matplotlib, seaborn y sklearn para procesamiento y visualización.
