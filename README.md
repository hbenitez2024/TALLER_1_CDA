# TALLER_1_CDA

## Instrucciones para Ejecutar el Notebook

Este documento proporciona instrucciones sobre cómo ejecutar el notebook que utiliza el archivo `listings.csv`. Dependiendo de si estás usando Google Colab o Visual Studio Code, sigue las instrucciones correspondientes.

### Ejecutar en Google Colab

Si estás trabajando en Google Colab, sigue estos pasos:

1. **Montar Google Drive**:
   Ejecuta el siguiente comando para montar tu Google Drive:

   ```python
   from google.colab import drive
   drive.mount('/content/drive')

2. **Navegar a la carpeta correcta**:
  Cambia el directorio actual a la carpeta donde se encuentra el archivo listings.csv. Reemplaza MyDrive/Taller 1/ con la 
  ruta correcta si es diferente.

   ```python
   %cd /content/drive/MyDrive/Taller 1/

### Ejecutar en Visual Studio Code

Si estás utilizando Visual Studio Code, simplemente necesitas especificar la ruta relativa del archivo listings.csv desde la ubicación del script o notebook que estás ejecutando. Asegúrate de que el archivo listings.csv se encuentre en la misma carpeta o proporciona la ruta correcta.

   ```python
   import pandas as pd
   listings_df = pd.read_csv("listings.csv", sep=',')
   ```

### Notas
* Asegúrate de tener instaladas las librerías necesarias, como pandas, en tu entorno de trabajo.
* Si necesitas realizar análisis adicionales, asegúrate de revisar la documentación de pandas para más funciones y métodos útiles.
