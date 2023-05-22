# **Proyecto Microsoft Malware Prediction**


## **Miembros del grupo:**
- María Paula Rojas Ortega
  
  *CC 1017255380*
  
  *Ingeniería ambiental*
- Juan Camilo Castañeda Ospina 
  
  *CC 1036966151*
  
  *Ingeniería civil*

## **Datos:**
Los datos del proyecto vienen de la competición de Kaggle Microsoft Malware Prediction (https://www.kaggle.com/competitions/microsoft-malware-prediction/data) y se pueden obtener si se ejecuta el siguiente código:

    !pip install gdown

    import gdown

    # Define ID del archivo en Google Drive
    archivo_id = "1---uAT4gEpKpJf9DPRC7VSQAsE9oAk-A"

    # Asigna nombre para el archivo en Colab
    d1 = "dataset_1.csv"

    # Construye el enlace de descarga del archivo
    enlace_descarga = "https://drive.google.com/uc?id=" + archivo_id

    # Descarga el archivo desde el enlace de descarga y lo guarda en Colab
    gdown.download(enlace_descarga, d1, quiet=False)
    
    #Lee el archivo y lo almacena en un DataFrame
    d = pd.read_csv("dataset_1.csv") 
    
 **Nota al margen: Cada notebook tiene este código al inicio, sin embargo, en los notebook de los modelos se usa el resultado del preprocesado (dataset_2.zip), y para las pruebas de llenado de datos faltantes, se usa el resultado del preprocesado antes del llenado (dataset_pp.csv)**

## **Videos:**
- Entrega 1:

https://youtu.be/gr1bFmMOrwg
