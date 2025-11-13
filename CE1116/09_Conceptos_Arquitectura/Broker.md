---
id: Broker
aliases: []
tags: []
date-created: "2025-11-12"
last-modified: "2025-11-12"
---



## 📚 Idea/Concepto 
El broker es un componente que actúa como un intermediario ligero encargado de distribuir 
el flujo de mensajes. Cuando un evento inicial comienza el proceso, este se publica en un 
canal del bróker, que lo distribuye mediante un mecanismo de broadcast a todos los 
procesadores de eventos interesados. En esta configuración no existe un mediador central 
que gestione el flujo de trabajo, lo que permite que los procesadores actúen en paralelo, 
reaccionando de manera independiente y asíncrona ante los eventos recibidos. Este modelo 
promueve un bajo acoplamiento entre emisores y receptores, lo que reduce la carga cognitiva 
al modificar componentes y mejora la escalabilidad y la mantenibilidad del sistema. Además, 
cada procesador puede generar nuevos eventos de procesamiento, que se publican nuevamente en 
el bróker para continuar el flujo asincrónico y facilitar la expansión dinámica del sistema. 
Para garantizar confiabilidad en un entorno distribuido, los procesadores deben diseñarse 
como idempotentes, de modo que la repetición de mensajes o fallos no afecte la consistencia 
del sistema. Asimismo, el uso de un event log permite conservar el historial de mensajes, 
facilitando la reproducción o incorporación de nuevos servicios que consuman eventos 
pasados, consolidando así la resiliencia y la trazabilidad del sistema.

## 📌 Puntos Claves (Opcional)
- Distribucion Asincornica
- Eventos

## 🔗 Connections
- [[Acoplamiento]]
- [[Arquitectura Event Driven]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 

