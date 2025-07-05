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

Para ejecutar el notebook en google Colab.


