# Movies and Jokes
Desarrollado en el curso Reconocimiento de patrones en Minería de Datos por: Stephanie Riff y Kevin Reyes.
## Objetivos
- Recomendar películas y chistes a un usuario en base a sus preferencias.
- Aplicar métodos de recomendación de filtrado colaborativo basados en usuarios y en items.
- Evaluar la cantidad de vecinos cercanos a utilizar para obtener una buena recomendación.
- Comparar los métodos de filtrado colaborativo basados en usuarios y en items.

## Descripción
Sistema recomendador de películas y chistes utilizando métodos de filtrado colaborativo basado en usuarios e items.

## Conclusiones
- En métodos de filtrado colaborativo basados en usuarios, si el usuario ha visto películas conocidas, recibirá recomendaciones de películas conocidas. En cuanto a chistes, se comprueba que si al usuario le gustan chistes asociados a profesiones, entonces se le recomendarán más usuarios relacionados a profesiones.
- El filtrado colaborativo basado en items puede tener un mejor rendimiento en sistemas reales donde el número de items es << que el número de usuarios.
- Es de suma importancia considerar el sesgo de cada usuario al momento de realizar recomendaciones.

## Stack de tecnologías
- Pandas.
- Numpy.
- Scikit-learn.