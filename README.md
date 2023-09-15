# Etapa_2
Unidad 1 - Etapa 2 - Diseño de sistemas de aprendizaje automático
# Proyecto de Regresión Lineal en Python

Este proyecto es un ejemplo de cómo realizar una regresión lineal simple en Python utilizando las bibliotecas populares como Matplotlib, Scikit-Learn, Seaborn, NumPy y Pandas. La regresión lineal es una técnica de aprendizaje automático que se utiliza para predecir una variable dependiente (en este caso, el precio) basada en una o más variables independientes (en este caso, el metro).

## Requisitos

Para ejecutar este proyecto, asegúrate de tener instaladas las siguientes bibliotecas de Python:

- Matplotlib
- Scikit-Learn (sklearn)
- Seaborn
- NumPy
- Pandas

Puedes instalar estas bibliotecas utilizando el administrador de paquetes `pip`. Por ejemplo:

```bash
pip install matplotlib scikit-learn seaborn numpy pandas


# Regresión Logística para la Predicción de Enfermedades Cardíacas

Este proyecto utiliza un modelo de regresión logística para predecir el riesgo de enfermedades cardíacas en función de diferentes características de los pacientes. Se emplea el conjunto de datos proporcionado para entrenar y evaluar el modelo.

## Contenido

- [Requisitos](#requisitos)
- [Instrucciones de Uso](#instrucciones-de-uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Resultados](#resultados)
- [Referencias](#referencias)

## Requisitos

Antes de ejecutar el código, asegúrate de tener instaladas las siguientes bibliotecas de Python:

- pandas
- scikit-learn

Puedes instalar estas bibliotecas utilizando `pip`:


## Instrucciones de Uso

1. Clona o descarga este repositorio en tu máquina local.

2. Asegúrate de tener el archivo de datos (`tu_archivo.csv`) en la misma ubicación que tu script de Python.

3. Ejecuta el script de Python (`regresion_logistica.py`) para entrenar el modelo y obtener las métricas de evaluación.

4. El resultado del modelo se mostrará en la consola, incluyendo la precisión, la matriz de confusión y el informe de clasificación.

## Estructura del Proyecto

- `tu_archivo.csv`: El archivo de datos que contiene las características y la variable objetivo.
- `regresion_logistica.py`: El script de Python que realiza el preprocesamiento de datos, entrena el modelo y evalúa su rendimiento.
- `README.md`: Este archivo de documentación.

## Resultados

El modelo de regresión logística ha sido entrenado y evaluado con los siguientes resultados:

- Exactitud (Accuracy): 0.857
- Matriz de Confusión:
[[718 6]
[115 9]]

- Informe de Clasificación:
-           precision    recall  f1-score   support

       0       0.86      0.99      0.92       724
       1       0.60      0.07      0.13       124

accuracy                           0.86       848


macro avg 0.73 0.53 0.53 848
weighted avg 0.82 0.86 0.81 848


## Referencias

- [Documentación de scikit-learn](https://scikit-learn.org/stable/)
- [Guía de scikit-learn sobre imputación de valores faltantes](https://scikit-learn.org/stable/modules/impute.html)


