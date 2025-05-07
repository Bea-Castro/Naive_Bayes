Este proyecto utiliza Naive Bayes para clasificar reseñas de  Google Play Store para predecir si un comentario es positivo o negativo.

En él evaluamos los 3 modelos de Naive Bayes:

- GaussianNB (Distribución Normal)
- MultinomialNB (distribución de frecuencia de palabras)
- BernoulliNB (presencia o ausencia de palabras)

Tras evaluar los resultados, se selecciona la mejor alternativa para posteriormente intentar mejorar el rendimientio aplicando Random Forest.

Finalmente se exploran ootros modelos y se realiza una comparación para quedarnos con el que obtiene mejores resultados en accuracy y guardamos el modelo.

Los datos para resolver el problema se han sacado del siguiente enlace: 

https://raw.githubusercontent.com/4GeeksAcademy/naive-bayes-project-tutorial/main/playstore_reviews.csv

La solución se ecuentra en la carpeta SRC en el jupiter notebook llamado "explore.ipynb".
