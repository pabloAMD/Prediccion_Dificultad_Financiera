# Prediccion_Dificultad_Financiera

Un cuaderno de Jupyter que demuestra el desarrollo de un modelo de red neuronal y modelos SVM lineal, polinomial y sigmoide. 
Los cuadernos utilizan el conjunto de datos proporcionados por Kagle [1], que contienen 86 columnas de datos en base a un historial 
en base al tiempo de situaciones de empresas con el fin de predecir una dificultad financiera, logramos crear un modelo de red neuronal mediante  50 epochs y
un modelo de soporte de máquinas vectoriales(SVM) que obtienen 0.9660 y 0.9630 aplicando la medida de calidad de accuracy.

El cuaderno a sido desarrollado en Google Colaboratory que es un entorno gratuito de Jupyter Notebook que no requiere 
configuración y que se ejecuta completamente en la nube de forma gratuita y proporciona el siguiente flujo de trabajo:

- ProyectoFinal: carga y reducción de dimensionalidad mediante el algoritmo de componentes principales de dataset [1], creacion de un modelo de red neuronal y modelos SVM, 
para realizar los respectivos análisis y comparaciones.


## Requisitos

- Python
- Financial Distress Prediction : Dataset.

## Dependencias
- numpy
- pandas
- sklearn
- matplotlib
- tensorflow

## Referencia
[1] Financial Distress Prediction : Dataset. https://www.kaggle.com/shebrahimi/financial-distress/data?select=Financial+Distress.csv 
