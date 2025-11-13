---
id: Arquitectura en capas
aliases: []
tags: []
date-created: "2025-11-12"
last-modified: "2025-11-12"
---



## 📚 Idea/Concepto 
La arquitectura en capas es un estilo de organización del software en el que los componentes 
de un sistema se agrupan en capas lógicas horizontales, cada una con responsabilidades específicas. 
Su objetivo principal es gestionar la complejidad de la aplicación mediante la aplicación del 
principio de Separación de Responsabilidades, lo que permite lograr un bajo acoplamiento y 
una alta cohesión entre los componentes. En este modelo, la capa de Presentación se encarga de 
gestionar las interacciones del usuario y la interfaz; la capa de Lógica de Negocio constituye 
el núcleo central donde se implementan las reglas y se procesan los datos; y la capa de Acceso 
a Datos se ocupa de definir cómo la información se almacena y se recupera de los sistemas de 
persistencia. Además, la arquitectura en capas establece reglas claras de comunicación entre 
los distintos niveles, que pueden adoptar un esquema de interacción estricta, donde cada capa 
se comunica únicamente con la inmediatamente inferior, o una interacción suelta, que permite 
una comunicación más flexible para optimizar el rendimiento y la reutilización de componentes. 
Asimismo, promueve el uso de interfaces bien definidas para gestionar dependencias, lo que 
contribuye directamente a mejorar la modificabilidad, la testabilidad y la escalabilidad del sistema.

## 📌 Puntos Claves (Opcional)
- Separacion de Responsabilidades 
- Capa Presentacion
- Capa Lógica de Negocio
- Capa PErsistencia 
- Capa Crosscutting
 
## 🔗 Connections
- [[Arquitectura Event Driven]]
- [[Arquicturua Microkernel]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 

