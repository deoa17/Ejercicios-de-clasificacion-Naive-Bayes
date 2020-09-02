# Ejercicios-de-clasificacion-Naive-Bayes

Realizamos dos ejercicios de clasificacion usando Naive Bayes y NLP

1. Ejercicio de práctica: Clasificación de palabras por género
Objetivo: Construye un classificador de nombres en español usando el siguiente dataset: https://github.com/jvalhondo/spanish-names-surnames

* Preparación de los datos: con un git clone puedes traer el dataset indicado a tu directorio en Colab, luego asegurate de darle el formato adecuado a los datos y sus features
* Entrenamiento y performance del modelo: usando el classificador de Naive Bayes de NLTK entrena un modelo sencillo usando el mismo feature de la última letra del nombre, prueba algunas predicciones y calcula el performance del modelo
* Mejores atributos: Define una función como atributos2() donde puedas extraer mejores atributos con los cuales entrenar una mejor version del clasificador. Haz un segundo entrenamiento y verifica como mejora el performance de tu modelo. ¿Se te ocurren mejores maneras de definir atributos para esta tarea particular?

2. Clasificación de documentos (email spam o no spam)
Objetivo: Construye un classificador usando los corpus del siguiente dataset: https://github.com/pachocamacho1990/datasets 

* Limpieza: como te diste cuenta no hicimos ningun tipo de limpieza de texto en los correos electrónicos. Considera usar expresiones regulares, filtros por categorias gramaticales, etc ...
* Validación del modelo anterior: Una vez tengas el nuevo conjunto de datos más pulido y de mayor tamaño, considera el mismo entrenamiento con el mismo tipo de atributos del ejemplo anterior, ¿mejora el accuracy del modelo resultante?

