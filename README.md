# Challenge-3-Evasion-de-clientes
***Que es este proyecto***





#*Este codigo muestra un analisis de la baja de clientes de una empresa en telecomunicaciones, y esta basado en tecnicas de analisis de datos y herramientas de machine learning
Primeramentre se cargaron los datos de un archivo JSON*



Luego, se revisaron y se hizo una limpieza de los valores vacios, segun corresponde, para los cargos que se mostraban como nulos se hizo una sustitucion por el promedio del valor anterior y el siguiente.
Se debio hacer un encoding, para minimizar el ruido que variables de mayor valor le puedan generar a los modelos de marchine learning
Se realizo un analisis de correlaciones para verificar cuales son las variables cuantitativas que mas peso tienen en el cambio de la variable de respuesta, donde se ha encontrado que una de las variables a observar son los montos totales y mensuales, dicho sea de paso estan relacionados entre si.
El primer modelo es un arbol de decision, donde tambien se evalua que tanto el modelo esta prediciendo de manera correcta. Se separaron datos de entrenamiento de prueba, asi como datos de validacion para observar que tan exacto esta siendo el modelo, con respecto a los tipo de error. Tambien se probo el modelo con una pipeline para identificar que estaba prediciendo los datos de manera aceptable.
El segundo modelo es un knn, donde tambien se pone a prueba que tan exacto esta siendo en la prediccion, para asi poder comparar con el modelo de arboles de decision.
De los dos modelos se analizan que variables tienen mas peso, para recomendarle a la compania donde atacar y que tipo de cliente debe cuidar mas
