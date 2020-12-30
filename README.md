# Proyecto: Análisis exploratorio y predictivo en el Data Set del Titanic. 
 
* Primero vamos a abordar las variables relevantes para clasificar la supervivencia de un pasajero en el Titanic. En seguida se hará un pre-procesamiento que se dividirá en:  
 
    * Análisis descriptivo. 
    * Outliers. 
    * Nuevas variables. 
    * Selección de variables, para el entrenamiento de nuestros modelos. 
 
 >_**Nota:**_ Para ver más detalles del proceso consultar la el código en la carpeta Code de este mismo repo. Aquí, sólo se mostrarán los resultados. 
 
Bueno, a manera de conclusión de los pos pasos anteriores, mostraremos cómo están correlacionadas entre sí, ya para pasar al modelamiento: 
 
![1](https://user-images.githubusercontent.com/63415652/103332391-5bdc1380-4a2f-11eb-8dce-d5a2c0df0fcf.PNG)
 
Aquí podemos observar que el valor más bajo de la correlación es para los valores más oscuros y el más alto para los más bajos. 
 
---
 
Ahora ya que se realizó en análisis exploratorio, pasaremos al **análisis predictivo.** 
 
En este caso usaremos 2 modelos para medir la precisión de cada uno. En este caso nos enfrentamos a un problema de clasificación, así que usaremos regresión logística y árboles de decisiones. 
 
El objetivo de esta clasificación es determinar el numero de supervivientes y para ello usaremos todos las demás variables restantes como edad, el numero de parientes, su sexo, etc. 
 
Ahora veremos cúal es el mejor modelo para predecir nuestra clasificación: 
 
![2](https://user-images.githubusercontent.com/63415652/103333099-46b4b400-4a32-11eb-9ee3-a2385ef86ffd.PNG)
 
Y el modelo que ganó en precisión fue la regresión logística. 
 
Y para finalizar, unas relaciones de las variables con que realizó la producción: 
 
![3](https://user-images.githubusercontent.com/63415652/103333392-76b08700-4a33-11eb-8bb6-da4a7c239bbd.PNG)
![4](https://user-images.githubusercontent.com/63415652/103333394-77491d80-4a33-11eb-9b39-d6214c2be378.PNG)
![5](https://user-images.githubusercontent.com/63415652/103333395-77e1b400-4a33-11eb-8794-c44b7ea06e7d.PNG)
 
En donde se puede notar una diferencia abismal es en el sexo, ya que en su momento para abordar los botes de emergencia priorizaban mucho “mujeres y niños”, la mayoría de los hombres, y sobre todo de la tercera clase, fueron dejados en el Titanic hasta su hundimiento.  








