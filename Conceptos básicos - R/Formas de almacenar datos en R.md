==Vectores==
	- Un vector es la estructura de datos más simple en R y se utiliza para almacenar elementos del mismo tipo.
	
	Por ejemplo podemos escribir esto:
	mi_primer_vector <- c(1, 2, 3, 4, 5)

==Matrices==
	- Es una estructura de datos bidimensional que contiene elementos del mismo tipo. Se puede pensar en una matriz como una tabla con filas y columnas. Para crear una matriz, podemos utilizar la función `matrix()`.
	
	Por ejemplo podemos escribir esto:
	mi_matriz <- matrix(c(1, 2, 3, 4, 5, 6), nrow = 2, ncol = 3)

==Listas==
	- A diferencia de vectores o matrices, las listas permiten almacenar elementos heterogéneos. Es una estructura de datos que puede contener elementos de diferentes tipos, como números, caracteres, factores, otras listas, etc.
	
	Por ejemplo podemos escribir esto:
	lista_ simple <- list(1, "texto", TRUE, c(2, 4, 6), factor("A"))
	lista_nombres <- list(nombre = "Juan", edad = 25, ciudad = "Nueva York")

==Dataframe==
	- Es una estructura de datos bidimensional, se utiliza para almacenar y organizar datos de manera tabular. Podemos verla como una tabla en una base de datos o una hoja de cálculo, donde cada columna puede ser de un tipo diferente.
	
	Por ejemplo podemos escribir esto:
	mi_primer_dataframe <- data.frame( Nombre = c("Juan","María","Carlos"), 
	Edad = c(25, 30, 28), 
	Ciudad = c("Nueva York", "Los Ángeles", "Chicago") )