---
id: Arquicturua Microkernel
aliases: []
tags: []
date-created: "2025-11-12"
last-modified: "2025-11-12"
---



## 📚 Idea/Concepto 
También llamada Plug-In, es un estilo de arquitectura que se estructura alrededor de un núcleo 
central o sistema básico que contiene la funcionalidad mínima y esencial necesaria para 
ejecutar el sistema, y un conjunto de componentes externos o plug-ins que amplían o 
personalizan su comportamiento. Esta división permite mantener un núcleo simple y estable, 
mientras que las funciones adicionales o especializadas se implementan como módulos 
independientes que pueden añadirse, modificarse o eliminarse sin afectar el sistema principal. 
Los plug-ins se utilizan específicamente para aislar el código altamente volátil, facilitando 
su mantenimiento y mejorando la capacidad de prueba dentro de la aplicación, al tiempo que 
promueven una arquitectura más modular y flexible.
Además, esta arquitectura incluye mecanismos que permiten la interacción entre el núcleo y los 
plug-ins. Entre ellos, destaca el Registro de Plug-ins (Registry), que actúa como un catálogo 
donde el núcleo puede descubrir qué módulos están disponibles y cómo acceder a ellos, y cuya 
implementación puede variar desde una estructura interna sencilla hasta un sistema de 
descubrimiento externo más complejo. Asimismo, cada plug-in debe cumplir con un Contrato que 
define las interfaces, datos de entrada/salida y comportamientos esperados, asegurando una 
comunicación coherente y segura entre los componentes. El cumplimiento de este contrato refuerza 
la separación entre interfaz e implementación, logrando un bajo acoplamiento que permite sustituir 
o modificar los plug-ins sin afectar la estabilidad del sistema. Estos mecanismos aseguran la 
extensibilidad, adaptabilidad y mantenibilidad del sistema en tiempo de ejecución.

## 📌 Puntos Claves (Opcional)
- Nucleo 
- Plug-In
- Contrato

## 🔗 Connections
- [[Acoplamiento]]
- [[Arquitectura en capas]]
- [[Arquitectura Event]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 

