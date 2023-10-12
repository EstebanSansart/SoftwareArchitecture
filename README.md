# Arquitectura De Software

¡Bienvenidos! En esta presentación, exploraremos en detalle los conceptos fundamentales de la arquitectura de software y las implicaciones que esto conlleva, por lo que tomará un buen tiempo abarcar y entender estos temas.
## Índice
## 1. ¿Qué es la Arquitectura de Software?

No existe una única definición de arquitectura de software debido a su naturaleza multifacética y a la evolución constante de la industria del software. Diversos expertos y profesionales pueden ofrecer definiciones ligeramente diferentes basadas en sus perspectivas y necesidades específicas. Además, la arquitectura de software puede variar considerablemente según el tipo de aplicación o sistema que se esté desarrollando, lo que también contribuye a la falta de una única definición.
## 2. Patrones de Diseño

Los patrones de diseño son soluciones comunes para problemas que surgen repetidamente en el diseño de software. Los puedes considerar como plantillas personalizables que te ayudan a resolver problemas de diseño recurrentes en tu código.

Es importante entender que no puedes simplemente copiar y pegar un patrón en tu programa como lo harías con funciones o bibliotecas predefinidas. Un patrón no es una pieza de código específica, sino más bien un enfoque general para abordar un problema particular. Debes adaptar los detalles del patrón e implementar una solución que se ajuste a las necesidades de tu propio programa.

A veces, los patrones se confunden con algoritmos, ya que ambos representan soluciones comunes para problemas conocidos. Sin embargo, hay una diferencia fundamental. Mientras que un algoritmo proporciona una secuencia de pasos claros para lograr un objetivo específico, un patrón es una descripción de nivel superior de una solución. Esto significa que el código que implementa el mismo patrón en dos programas diferentes puede ser distinto.

Para ilustrar esta diferencia, podríamos comparar un algoritmo con una receta de cocina, ya que ambos siguen pasos específicos para alcanzar un resultado deseado. Por otro lado, un patrón es más similar a un plano arquitectónico, donde puedes ver cómo debería ser el resultado final y cuáles son las funciones clave, pero la implementación exacta depende de ti y de las necesidades de tu proyecto.

### 2.1 ¿En qué consisten los Patrones de Diseño?

La mayoría de los patrones se describe con mucha formalidad
para que la gente pueda reproducirlos en muchos contextos.
Aquí tienes las secciones que suelen estar presentes en la de-
scripción de un patrón:

- El propósito del patrón explica brevemente el problema y la solución.
- La motivación explica en más detalle el problema y la solución que brinda el patrón.
- La estructura de las clases muestra cada una de las partes del patrón y el modo en que se relacionan.
- El ejemplo de código en uno de los lenguajes de programación populares facilita la asimilación de la idea que se esconde tras el patrón.

Algunos catálogos de patrones enumeran otros detalles útiles, como la aplicabilidad del patrón, los pasos de implementación y las relaciones con otros patrones.

### 2.2 Ejemplos de Patrones de Diseño

- Patrón Singleton: Este patrón garantiza que una clase solo tenga una instancia.
- Patrón Factory: Este patrón proporciona una forma de crear objetos sin exponer la lógica de creación.
- Patrón Adaptador: Este patrón permite que dos objetos que no son compatibles interactúen entre sí.
## 3. Patrones Arquitectónicos

Un patrón arquitectónico es una solución a un problema recurrente en el diseño de software. Es un esquema de organización estructural que define subsistemas, sus responsabilidades e interrelaciones. Los patrones arquitectónicos proporcionan una visión general de alto nivel de un sistema de software, y ayudan a los desarrolladores a tomar decisiones sobre la estructura y el diseño de su sistema.

### 3.1 Ejemplos de Patrones Arquitectónicos

- Arquitectura por capas: Esta arquitectura divide un sistema de software en capas, cada una de las cuales tiene una responsabilidad específica.
- Arquitectura cliente-servidor: Esta arquitectura divide un sistema de software en un cliente, que interactúa con el usuario, y un servidor, que proporciona servicios al cliente.
- Arquitectura en microservicios: Esta arquitectura divide un sistema de software en un conjunto de servicios independientes que se comunican entre sí a través de una API.

### 3.2 Diferencias entre Patrones de Diseño y Patrones Arquitectónicos

- Ámbito: Los patrones arquitectónicos se aplican a sistemas de software completos, mientras que los patrones de diseño se aplican a clases y objetos individuales.
- Complejidad: Los patrones arquitectónicos suelen ser más complejos que los patrones de diseño.
- Especificación: Los patrones arquitectónicos suelen ser menos específicos que los patrones de diseño.

![SCREENSHOT_PATRONES_ARQUITECTONICOS]()