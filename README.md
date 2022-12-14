# APC-Kaggle-NewYork_City_Airbnb_Data

# Práctica Kaggle APC UAB 2022-23
### Nombre: Javier Méndez Leiva ### DATASET: 70 - NewYork_City_Airbnb_Open_Data
### URL: [kaggle] https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data

## Resumen
El dataset presenta 16 columnas con 6 de ellas siendo parámetros categóricos, otros son parámetros numéricos de los cuales se tuvo que aplicar una normalización a ciertos valores para computar una media y en otro caso se substituyeron los NaN por ceros por tal de rellenar los huecos debido a la lógica de los valores respecto a otra columna.
Por otro lado tenemos que los valores categóricos se han convertido a numerales por tal de poder efectuar el análisis.

## Objetivos del dataset
Según se fue avanzando en el análisis de datos cada vez se concluyó mas que se efecturía un intento de un modelo de predicción del precio en base al vecindario y el tipo de habitación, demostrandose generalmente bastante posible a lo largo del mismo

## Experimentos
Durante este ejercicio se han efectuado múltiples experimentos, algunos se han desestimado según se avanzaban y algunos de ellos se han debido corregir debido a la inexperiencia que aún presento en este campo.
Es por esto que entre los descartados encontramos el análisis de los precios y las reservas en base a las palabras seleccionadas en el nombre, experimento que se indicó como interesante debido a que podía indicar las tendencias de las personas a seleccionar X destinos en base a ciertas palabras.
Otro experimento descartado porque se consideraba poco interesante fue el del impacto en las reservas que presenta la disponibilidad de los domicilios indicados.
Finalmente el llevado a cabo y ya indicado es el de predecir precio en base a vecindario y tipo de habitación el cual comprende un análisis y prueba profunda de tanto el mejor modelo a nivel de resultados como de mejora mediante hiperparámetros de los mismos.

## Modelos
Durante el análisis se han usado múltiples modelos de regresión, los usados son los listados a continuación:
-Linear Regressión
-Random Forest Regressor
-Lasso Regression
-Ridge Regression
-Decision Tree Regressor

## Demo
Para obtener una demostración se recomienda ojear el fichero Analisis.ipynb, el cual gracias a github cuenta con los parámetros resultantes de la ejecución fijados con las gráficas obtenidas durante el mismo.

## Ideas para trabajar en un futuro
Por tal de obtener mas detalle sobre el valor de los datos se considera que el experimento de los nombres podría proporcionar información valiosa, también es posible que del mismo modo que se ha hecho un modelo predictivo fuese posible efectuar un modelo clasificador haciendo uso del precio y el tipo de habitación para determinar la población en la que se encuentra.

## Conclusión
El modelo que obtuvo el mejor resultado es el Random Forest, pienso que este es el que desde inicio iba a presentar mejores resultados debido a su capacidad de gestionar grandes volumenes de datos.
En comparación con los otros resultados, si es cierto que tenemos resultados relativamente parejos pero tenemos un problema mucho mas presente y visible de overfitting.
