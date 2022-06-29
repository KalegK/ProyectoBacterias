# ProyectoBacterias
Este repositorio esta destinado al desarrollo de una red neuronal con embedding, para el tratamiento de datos de bacterias, obtenidas a traves de espectrometría de masas con la tecninca MALDI-TOF. Este proyecto aun sigue en desarrollo(fase inicial).

<h1>Composición</h1>

El repositorio esta compuesto(de momento) por 3 archivos y una carpeta:
1. **Untitled.ipynb**: Contiene el codigo desarrollado en libros de jupyter, en el que se manejan los datos de las bacterias. En este repositorio solo esta una pequeña porción de los datos a manejar.
2. **Output.csv**:Archivo csv que contiene la matriz resultante de la escritura de los dataframes realizadas en Untitled.ipynb.
3. **2018_clean.csv**:Archivo csv que contiene la metadata de las bacterias. En este archivo se puede encontrar el codigo, specie, resistencia antibiotica, entre otros.
4. **Muestras**:Carpeta contenedora de las muestras en formato txt, en los cuales se encuentra el codigo asociado a la bacteria, sus masas e intensidades. En el ambito de este proyecto se trabajara con la columna de intensidades('intensity').

<h1>Pre-requisitos</h1>
-Pandas instalado.

<h1>Despliegue</h1>
Para ejecutar el codigo, se debe contener Untitled.ipynb, la carpeta Muestras y el 2018_clean.csv, dentro de un mismo directorio. Y luego dentro de simbolos del sistema ejecutar Jupyter Notebook, para la posterior ejecución de Untitled.ipynb.

