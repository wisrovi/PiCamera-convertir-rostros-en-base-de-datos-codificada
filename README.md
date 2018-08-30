# PiCamera-convertir-rostros-en-base-de-datos-codificada

Para este proyecto vamos a continuar donde lo dejamos en el proyecto anterior.
El proyecto anterior esta en https://github.com/wisrovi/CapturarRostroPiCamara

# Antes de iniciar vamos a instalar las bibliotecas que se usaran:

pip3 install face_recognition
pip3 install face_recognition_models

# continuando...

Antes, con la PiCamera tomamos una fotografia y con el haarcascade de OpenCV detectamos el rostro, luego creamos una imagen con el rostro de la (s) personas detectadas y estas imagenes las guardabamos  en una carpeta llamada pictures_of_people_i_know.

En esta oportunidad y con la ayuda de la biblioteca para python3 face_recognition vamos a codificar todos los rostros de una carpeta (uno a uno)  y estos los vamos a guardar en un archivo data.csv y nombres.csv para tener una base de datos de personas en formato array() para cada una.

Estas bases de datos las vamos a guardar en una carpeta llamada temporal.

el archivo principal que vamos a usar es actualizarDatosRF.py este importara los demas archivos y sus funciones
