# Práctica 2: Limpieza y validación de los datos - horse_colic_study

## Descripción
En este repositorio se presenta el código que limpia y estudia datos sobre casos de cólicos en caballos extraídos del repositorio de datos de [University California Irvine] (https://archive.ics.uci.edu/ml/index.php).

Este trabajo se ha realizado bajo el contexto del máster de Ciencia de Datos de la UOC. En concreto, responde al enunciado de la Práctica 2 de la asignatura de _Tipología y Ciclo de Vida de los Datos_.

## Miembros del equipo
Esta práctica ha sido realizada por los alumnos **Daniel Mato Regueira** e **Iago Veiras Lens**.

## Ficheros del repositorio

- **csv/horse-colic.data** y **csv/horse-colic.test** : ficheros de entrada _.data_ con la información extraída de la web.
- **csv/clean_data_horse_colic.csv** : fichero de salida _.csv_ resultado de aplicar las técnicas de limpieza a los ficheros de input.
- **pdf/Practica_2_Respuestas.pdf**: documento _pdf_ con las respuestas a las preguntas del enunciado de la práctica.
- **Practica2.Rmd**: fichero principal en donde se encuentran los comandos para la resolución de la práctica.

## Ejecución
Antes de ejecutar el programa es necesario tener instalado los siguientes paquetes:

```rubi
install.packages("VIM")
install.packages("mice")
install.packages("car")
install.packages("dummies")
install.packages("corrplot")
install.packages("RColorBrewer")
install.packages("caret")
install.packages("pROC")
```
Una vez instados los paquetes, podemos ejecutar los comandos para la resolución de los ejercicios.
