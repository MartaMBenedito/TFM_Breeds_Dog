# TFM 16ª Ed Máster Data Science Madrid Kschool
## Predicción de MVP de la NBA temporada 2019
### Introducción
En este TFM prentendemos, mediante la aplicación de Modelos estadísticos de Machine Learning supervisado predecir qué jugador de la NBA será MVP para la actual temporada a traves de sus datos estadísticos.

### Descripción de datos
Los datos que vamos a necesitar serán:
* Estadísticas individuales por jugador de la temporada actual
* Estadísticas y votos de los ganadores MVP de temporadas anteriores
Todos los datos los encontramos en www.basketball-reference.com

### Metodología:
Utilizaremos Supervised Machine Learning con Python, a traves de parejas de vectores etiquetados, entrenaremos y comprobaremos nuestros modelos.

El vector Input (X) contendrá las estadísticas de los jugadores finalistas y ganadores de las temporadas anteriores.

El vector Output (Y), contendrá la etiqueta de la puntuacion asignada como premio (share_awards)

El resultado de la relacion entre X e Y será una Regresión, pues el dato que esperamos es una variable continua, no una clasificación del dato.

#### Tipos de modelos
Regression:
Linear Regression
k neighbor Regressor
Decision Tree Regressor
Gradient Boosting Regressor
#### Metricas
Regression:

RMSE (Root Mean Square Error)
MAE and MAPE (Mean Absolute Error, Mean Absolute Percent Error)
Correlation and Bias
#### Herramientas necesarias
El proyecto ha sido creado con Python desde el paquete Anaconda. Se puede ejecutar desde cualquier Power Shell desde Jupyter Notebook.

Es necesario tener instalado Anaconda3 con las dependencia y librerias siguientes:

Jupyter Notebook

Python (3.7.3)

Pandas (5.7.8),
Numpy (1.16.2),
Matplotlib (3.0.3),
Seaborn (0.9.0),
Scikit Learn (0.20.3),

### Ejecución del proyecto
Para ejecutar el proyecto, abriemos una sesion de Jupyter y ejecutaremos el fichero NBA_MVP.ipynb.

### Resultado / Frontend
El resultado del proyecto, será una lista con los 10 jugadores actuales de la presente temporada con la mayor predicción para ser el MVP de la NBA 2019-20.
