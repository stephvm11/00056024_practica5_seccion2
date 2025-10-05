# Resolución de preguntas
## Ejercicio 5
### Veamos los resultados y pensemos ¿Qué significa className en React? ¿las props tienen un limite? ¿Quién define las props?
- "className" es un atributo para asignar clases CSS a un elemento HTML, se llama de esa manera para no generar conflictos con la palabra reservada "class" que se usa para definir clases de JS.
- Las props no tienen un límite en sí en React, pero si es recomendable no utilizar demasiadas para no recargar el componente y que sea mantenible.
- Las props son definidas por el componente padre, el cual pasa datos al componente hijo para ser renderizado y definir su comportamiento.
