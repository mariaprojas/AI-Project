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
    archivo_id = "1tQl5NDSp6TPxqDiUe342dYhC1j8yRg-v"

    # Asigna nombre para el archivo en Colab
    d1 = "dataset_1.csv"

    # Construye el enlace de descarga del archivo
    enlace_descarga = "https://drive.google.com/uc?id=" + archivo_id

    # Descarga el archivo desde el enlace de descarga y lo guarda en Colab
    gdown.download(enlace_descarga, d1, quiet=False)
    
    #Lee el archivo y lo almacena en un DataFrame
    d = pd.read_csv("dataset_1.csv") 
    
 **Nota al margen: Cada notebook tiene este código al inicio, sin embargo, en los documentos de prueba se usa el notebook resultado del preprocesado(dataset2.csv).**

## **Videos:**
- Entrega 1:

https://youtu.be/gr1bFmMOrwg
