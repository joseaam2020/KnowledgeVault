---
id: Arquitectura Event Driven
aliases:
  - Arquitectura Event Driven
tags: []
---

# Arquitectura Event Driven
---
id: Arquitectura Event Driven
aliases: []
tags: []
date-created: 2025-11-12
last-modified: 2025-11-12
---



## 📚 Idea/Concepto 
La EDA es un estilo de organización de la aplicación que se concentra en observar la interacción 
de un sistema con su mundo exterior como transmisiones de eventos, logrando que el sistema 
reaccione a lo que sucede. En este contexto, un evento se entiende como una declaración 
inmutable de un hecho, cuya publicación puede ser recibida por uno o varios componentes. La EDA 
se compone de componentes de procesamiento de eventos que tienen la función específica de recibir 
y procesar dichos eventos de forma asíncrona, lo que permite un bajo acoplamiento entre emisores 
y receptores, ya que estos no dependen entre sí ni en identidad ni en tiempo. Este estilo 
arquitectónico puede adoptar distintas topologías de coordinación, como la basada en Mediador u 
Orquestador, donde un componente central gestiona el flujo de eventos, o la basada en Broker, 
donde los eventos se distribuyen sin un mediador central, fomentando la escalabilidad y la 
independencia de los servicios. La comunicación suele implementarse mediante el modelo 
publicar/suscribir (pub/sub), que facilita la conexión de nuevos microservicios al sistema y 
habilita el procesamiento distribuido. Además, la naturaleza inmutable de los eventos está 
estrechamente vinculada con el patrón Event Sourcing, que permite reconstruir el estado del 
sistema a partir de la corriente de eventos y generar modelos derivados para diferentes propósitos.

## 📌 Puntos Claves (Opcional)
- Eventos 
- Bajo [[Acoplamiento]]
- Mediator 
- [[Broker]]

## 🔗 Connections
- [[Arquitectura en capas]]
- [[Arquicturua Microkernel]]
- [[Acoplamiento]]
- [[Broker]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 

