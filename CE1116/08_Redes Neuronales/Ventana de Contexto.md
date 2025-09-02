---
id: Ventana de Contexto
aliases: []
tags: []
date-created: "2025-09-02"
last-modified: "2025-09-02"
---



## 📚 Idea/Concepto 
La ventana de contexto es la cantidad de tokens, o valores de [[Embeddings]], que una LLM 
puede utilizar dentro de su algoritmo de [[Attention]] para que el contexto influencie los 
valores probabilísticos de la salida, lo que se logra al calcular el producto punto entre las 
matrices de Query y Key, cuyo tamaño depende del cuadrado de la ventana. Los pesos 
resultantes se aplican sobre la matriz de valores (V), que es la encargada de transferir la 
información y actualizar los [[Embeddings]] iniciales en representaciones contextualizadas. 
De esta forma, la ventana permite que los [[Embeddings]] capten relaciones con otras 
palabras mediante múltiples cabezas de atención, cada una enfocada en distintos 
patrones del contexto. Además, gracias al positional encoding, se preserva el orden de la 
secuencia en los cálculos paralelos, aunque al ser finita, la ventana también limita la 
memoria del modelo y puede provocar pérdida de coherencia en interacciones largas. 

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Embeddings]]
- [[Attention]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 

