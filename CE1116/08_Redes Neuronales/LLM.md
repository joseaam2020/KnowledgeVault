---
id: LLM
aliases: []
tags: []
date-created: "2025-09-02"
last-modified: "2025-09-02"
---



## 📚 Idea/Concepto 
Los Large Language Models (LLMs) son [[Redes Neuronales]] dentro del campo de Deep 
Learning basadas en la arquitectura de transformers, entrenadas con cantidades masivas 
de datos que dan lugar a un número enorme de parámetros. A diferencia de otros tipos de 
redes, muestran una capacidad superior para la generación de texto gracias al uso de 
[[Embeddings]] iniciales y de los mecanismos de [[Attention]] propios de los transformers, los 
cuales permiten que cada representación vectorial se vea influenciada por el contexto en el 
que aparece mediante multiplicaciones de matrices, de Query y Key, junto con los vectores 
Value que contienen la información contextual a combinar, logrando así un mejor 
“entendimiento” del texto. Además, cuentan con dos elementos clave de la arquitectura: el 
multi-head attention, que permite procesar diferentes relaciones contextuales en paralelo, 
y el positional encoding, que incorpora el orden de las palabras en la secuencia, aspecto 
esencial para mantener el significado, junto con la capa feed forward que refina las 
representaciones. 

Estos modelos pasan por un proceso de preentrenamiento, altamente costoso por la 
cantidad de recursos computacionales necesarios, que produce un modelo base a partir 
del cual es posible realizar un ajuste posterior menos costoso conocido como finetuning, 
con el fin de especializar el LLM. En cuanto a su arquitectura, la capa de [[Embeddings]] genera 
las representaciones vectoriales iniciales de las palabras, que son refinadas 
posteriormente por el encoder o el decoder, según el tipo de modelo, de modo que los LLMs 
generativos como GPT utilizan únicamente la parte del decoder del transformer siguiendo 
un enfoque autorregresivo, mientras que otros como BERT emplean solo el encoder.  

Finalmente, aunque estos modelos han demostrado un rendimiento sobresaliente, 
presentan limitaciones importantes como la posibilidad de producir “alucinaciones”, o sea, 
información incorrecta.

## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Redes Neuronales]]
- [[Embeddings]]
- [[Attention]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 

