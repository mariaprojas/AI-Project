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

    !pip install gdown

    import gdown

    # Define ID 
    archivo_id = "1bEmU6l5uMKi3QOmJUgRaCCH_zqt4eZrW"

    # Asigna nombre para el archivo en Colab
    dtr1 = "train1M.csv"

    # Construye el enlace de descarga del archivo
    enlace_descarga = "https://drive.google.com/uc?id=" + archivo_id

    # Descarga el archivo desde el enlace de descarga y lo guarda en Colab
    gdown.download(enlace_descarga, dtr1, quiet=False)

    dtr = pd.read_csv("train1M.csv") 
