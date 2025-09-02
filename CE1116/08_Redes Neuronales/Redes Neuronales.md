---
id: Redes Neuronales
aliases: []
tags: []
date-created: "2025-09-02"
last-modified: "2025-09-02"
---



## 📚 Idea/Concepto 
Son un tipo de inteligencia artificial dentro del campo del machine 
learning, entre las cuales se encuentran las redes convolucionales, las recurrentes y los 
transformers, y aunque están inspiradas en las neuronas del cerebro humano, en realidad 
son modelos matemáticos que reciben el nombre de deep learning cuando cuentan con tres 
capas o más. Estas redes procesan entradas de números reales en forma de vectores que 
representan a los objetos de estudio, siendo llamadas [[Embeddings]] en el caso de palabras, 
y dichas entradas se transforman a través de sumas ponderadas dependientes de los pesos 
de la red, pasando por funciones de activación como ReLU o sigmoide, para finalmente 
convertirse en valores probabilísticos mediante la función softmax. 

Durante la fase de entrenamiento, la red utiliza conjuntos de datos de entrenamiento, 
validación y prueba con el fin de ajustar su comportamiento, aunque en este proceso puede 
presentar underfitting (cuando no logra aprender lo suficiente) u overfitting (cuando aprende 
de manera demasiado específica y no generaliza correctamente). El aprendizaje ocurre 
gracias a la función de costo y al algoritmo de backpropagation, que modifican los pesos y 
sesgos de la red para reducir la diferencia entre la predicción y la salida real, añadiendo 
además algoritmos de [[Attention]] en caso de los transformers, los cuales permiten cambiar 
el significado de un embedding según la [[Ventana de Contexto]] de modo que al concluir esta 
etapa se obtiene un modelo entrenado capaz de hacer predicciones sobre datos nuevos, lo 
que se conoce como fase de inferencia.

## 📌 Puntos Claves (Opcional)
-  

## 🔗 Connections
- [[Embeddings]]
- [[Attention]]
- [[Ventana de Contexto]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 

