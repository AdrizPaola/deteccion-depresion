
# Detección de la Depresión 

## Descripción del Contenido

* Data = Contiene los archivos .csv con los tweets depresivos y no depresivos.
* Embedding = Almacena el embedding en idioma español de dimensión 300.
* model = Archivo principal de tipo Jupyter Notebook, en donde se desarrollan los modelos y el preprocesamiento de datos.

## Requisitos Previos 
1. Descargar el dataset desde link: [Tweets Depresivos y No Depresivos en Español | Kaggle](https://www.kaggle.com/datasets/adrianapaola/tweets-depresivos-y-no-depresivos-en-espaol)
2. Descargar el embedding desde link: [Embedding - Español | Kaggle](https://www.kaggle.com/datasets/adrianapaola/embedding-espaol)
3. Colocar los archivos descargados dentro de la ubicación que le corresponde; La estructura del proyecto deberá lucir así: (asumiendo que la carpeta raíz es la resultante de clonar este repo)
	* deteccion-depresion
		* data 
			* pre_clean_d_tweets.csv
			* pre_clean_non_d_tweets.csv
		* embedding
			* SBW-vectors-300-min5.txt
		* model.ipynb
		* requirements.txt 
			
  

## Pasos para Correrlo
1. Instalar las librerías de Python necesarias con el comando:  `pip install requirements.txt`
2. Correr el script model.ipynb
