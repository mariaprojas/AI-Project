# **Proyecto Microsoft Malware Prediction**


## **Miembros del grupo:**
- María Paula Rojas Ortega
  *CC 1017255380*
  *Ingeniería ambiental*
- Juan Camilo Castañeda Ospina 
  *CC 1036966151*
  *Ingeniería civil*
- Daniela Gómez Correa
  *CC 1020452607*
  *Ingeniería ambiental*

## **Datos:**
Los datos del proyecto vienen de la competición de Kaggle Microsoft Malware Prediction (https://www.kaggle.com/competitions/microsoft-malware-prediction/data) y se pueden obtener si se ejecuta el siguiente código:

#En primer lugar se importan las librerias necesarias

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt 

import seaborn as sns

import random

import requests

import zipfile

import json

#Posteriormente se concede el acceso a los datos con credencial de cuenta Kaggle

data = {"username":"camilocasta58","key":"bf122c383b1a077cf251f3a08ec73ae7"}

with open('kaggle.json', 'w') as file:
   
        json.dump(data, file, indent=4)

#Acceso a Kaggle

! pip install kaggle

#Descarga de los datos

! mkdir ~/.kaggle

! cp kaggle.json ~/.kaggle/

! chmod 600 ~/.kaggle/kaggle.json

! kaggle competitions download -c microsoft-malware-prediction

#Abrir el archivo ZIP

with zipfile.ZipFile('microsoft-malware-prediction.zip', 'r') as zip_ref:
    
    # Extraer todos los archivos en la carpeta actual
   
      zip_ref.extractall('.')
