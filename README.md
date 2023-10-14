<div align="center">
    <h1>-SOFTWARE ARCHITECTURE-</h1>
    <p>¡Bienvenidos! En esta presentación, exploraremos en detalle los conceptos fundamentales de la arquitectura de software y las implicaciones que esto conlleva, por lo que tomará un buen tiempo abarcar y entender estos temas.</p>
</div>

<div>
    <h2 align="center">Índice</h2>
    <ul>
        <li>...</li>
    </ul>  
</div>

<div>
    <h2 align="center">1. ¿Qué es la Arquitectura de Software?</h2>
    <p>No existe una única definición de arquitectura de software debido a su naturaleza multifacética y a la evolución constante de la industria del software. Diversos expertos y profesionales pueden ofrecer definiciones ligeramente diferentes basadas en sus perspectivas y necesidades específicas. Además, la arquitectura de software puede variar considerablemente según el tipo de aplicación o sistema que se esté desarrollando, lo que también contribuye a la falta de una única definición.</p>
</div>

<div>
    <h2 align="center">2. Patrones de Diseño</h2>
    <p>Los patrones de diseño son soluciones comunes para problemas que surgen repetidamente en el diseño de software. Los puedes considerar como plantillas personalizables que te ayudan a resolver problemas de diseño recurrentes en tu código.

Es importante entender que no puedes simplemente copiar y pegar un patrón en tu programa como lo harías con funciones o bibliotecas predefinidas. Un patrón no es una pieza de código específica, sino más bien un enfoque general para abordar un problema particular. Debes adaptar los detalles del patrón e implementar una solución que se ajuste a las necesidades de tu propio programa.

A veces, los patrones se confunden con algoritmos, ya que ambos representan soluciones comunes para problemas conocidos. Sin embargo, hay una diferencia fundamental. Mientras que un algoritmo proporciona una secuencia de pasos claros para lograr un objetivo específico, un patrón es una descripción de nivel superior de una solución. Esto significa que el código que implementa el mismo patrón en dos programas diferentes puede ser distinto.

Para ilustrar esta diferencia, podríamos comparar un algoritmo con una receta de cocina, ya que ambos siguen pasos específicos para alcanzar un resultado deseado. Por otro lado, un patrón es más similar a un plano arquitectónico, donde puedes ver cómo debería ser el resultado final y cuáles son las funciones clave, pero la implementación exacta depende de ti y de las necesidades de tu proyecto.</p>

<h3>2.1 ¿En qué consisten los Patrones de Diseño?</h3>
<p>La mayoría de los patrones se describe con mucha formalidad para que la gente pueda reproducirlos en muchos contextos. Aquí tienes las secciones que suelen estar presentes en la de- scripción de un patrón:

- El propósito del patrón explica brevemente el problema y la solución.
- La motivación explica en más detalle el problema y la solución que brinda el patrón.
- La estructura de las clases muestra cada una de las partes del patrón y el modo en que se relacionan.
- El ejemplo de código en uno de los lenguajes de programación populares facilita la asimilación de la idea que se esconde tras el patrón.

Algunos catálogos de patrones enumeran otros detalles útiles, como la aplicabilidad del patrón, los pasos de implementación y las relaciones con otros patrones.</p>

<h3>2.2 Ejemplos de Patrones de Diseño</h3>
<p>

- Patrón Singleton: Este patrón garantiza que una clase solo tenga una instancia.
- Patrón Factory: Este patrón proporciona una forma de crear objetos sin exponer la lógica de creación.
- Patrón Adaptador: Este patrón permite que dos objetos que no son compatibles interactúen entre sí.</p>
</div>

<div>
    <h2 align="center">3. Patrones Arquitectónicos</h2>
    <p>Un patrón arquitectónico es una solución a un problema recurrente en el diseño de software. Es un esquema de organización estructural que define subsistemas, sus responsabilidades e interrelaciones. Los patrones arquitectónicos proporcionan una visión general de alto nivel de un sistema de software, y ayudan a los desarrolladores a tomar decisiones sobre la estructura y el diseño de su sistema.</p>

<h3>3.1 Ejemplos de Patrones de Arquitectónicos</h3>
<p>

- Arquitectura por capas: Esta arquitectura divide un sistema de software en capas, cada una de las cuales tiene una responsabilidad específica.
- Arquitectura cliente-servidor: Esta arquitectura divide un sistema de software en un cliente, que interactúa con el usuario, y un servidor, que proporciona servicios al cliente.
- Arquitectura en microservicios: Esta arquitectura divide un sistema de software en un conjunto de servicios independientes que se comunican entre sí a través de una API.</p>

<h3>3.2 Diferencias entre Patrones de Diseño y Patrones Arquitectónicos</h3>
<p>

- Ámbito: Los patrones arquitectónicos se aplican a sistemas de software completos, mientras que los patrones de diseño se aplican a clases y objetos individuales.
- Complejidad: Los patrones arquitectónicos suelen ser más complejos que los patrones de diseño.
- Especificación: Los patrones arquitectónicos suelen ser menos específicos que los patrones de diseño.</p>

<img src="https://user-images.githubusercontent.com/31961588/273664281-a1926874-7e0c-4f35-bb59-eaa8c749eb65.png" alt="patterns-img">

</div>

<div>
    <h2 align="center">4. Estilos Arquitectónicos</h2>
    <p>Los estilos arquitectónicos son un conjunto de conceptos y principios que sirven como guía para la construcción de sistemas de software. Se basan en la idea de que existen diferentes formas de organizar un sistema, cada una con sus propias ventajas y desventajas.

Los patrones arquitectónicos son soluciones a problemas comunes en la arquitectura de software. Proporcionan una descripción de los elementos y el tipo de relación que tienen, junto con un conjunto de restricciones sobre cómo pueden ser usados.

La diferencia principal entre estilos arquitectónicos y patrones arquitectónicos es su nivel de abstracción. Los estilos arquitectónicos son más generales y proporcionan una visión de alto nivel de cómo organizar un sistema. Los patrones arquitectónicos, por otro lado, son más concretos y proporcionan una solución específica a un problema particular.</p>

<h3>4.1 Ejemplos de Estilos Arquitectónicos</h3>
<p>

- Arquitectura en capas: El sistema se divide en capas, cada una con una responsabilidad específica.
- Arquitectura cliente-servidor: El sistema se divide en clientes y servidores, que se comunican entre sí.
- Arquitectura basada en eventos: El sistema se basa en la propagación de eventos entre los componentes.</p>

<h3>4.2 Relacionemos estos tres conceptos</h3>
<p>Los patrones de diseño, los patrones arquitectónicos y los estilos arquitectónicos son todos conceptos relacionados en la arquitectura de software. Aquí, existe una clase de jerarquía como la siguiente:</p>

<img src="https://user-images.githubusercontent.com/31961588/273671383-ded4fc19-ef72-4c8f-bf8b-edff99344e78.png" alt="hierarchy-img">
</div>