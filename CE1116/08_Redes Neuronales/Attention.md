---
id: Attention
aliases: []
tags: []
date-created: "2025-09-02"
last-modified: "2025-09-02"
---



## 📚 Idea/Concepto 
El mecanismo de atención de los Transformers, conocido como self-attention, es un 
algoritmo que, en términos simples, busca refinar el significado inicial dado por la capa de 
[[Embeddings]] y transformarlo en una representación más específica y dependiente de las 
relaciones con otras palabras de la secuencia. Esto se logra recibiendo los [[Embeddings]] 
iniciales, sumando la información de posición (positional encoding), y proyectando cada 
[[Embeddings]] en tres vectores distintos mediante matrices aprendibles: Query (Q), Key (K) y 
Value (V). Luego, se calcula el producto punto entre los Q y los K, se divide por un valor para 
estabilizar los valores, y se aplica softmax para normalizar y obtener los pesos de atención. 
Estos pesos se utilizan para combinar los vectores V en una suma ponderada, que forma la 
salida del mecanismo de atención.  

En el caso del multi-head attention, las salidas de cada cabeza se concatenan y se 
proyectan linealmente mediante una matriz de salida, ampliando la capacidad del modelo 
para asociar múltiples patrones de contexto en paralelo. Finalmente, esta representación 
se integra al [[Embeddings]] original a través de una conexión residual, lo que estabiliza el 
entrenamiento y permite que el modelo capture relaciones de manera más precisa. 
Además, se aplica una máscara que impide que cada posición acceda a información futura, 
garantizando que la generación sea secuencial y coherente.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Embeddings]]
- [[Redes Neuronales]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 

