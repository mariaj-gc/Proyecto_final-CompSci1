# Proyecto Final - CompSci1

*Integrantes*: José Felipe Sanabria, María José Giraldo
---
# Descripción del proyecto
Este proyecto, correspondiente a la asignatura de Computación Científica, busca aplicar los conocimientos y técnicas computacionales aprendidos en clase a las álgebras de representación. Más específicamente, se propone una aplicación de las álgebras de configuración de Brauer a la simulación de un sistema de transporte integrado en Bogotá.

Utilizando una base de datos generada con inteligencia artificial, que representa los tiempos que tarda este sistema en llegar a sus paradas establecidas, el tiempo que demora en recoger y dejar pasajeros, la demanda en cada estación, y otras variables relevantes, construimos una representación algebraica aplicada del sistema.

# Metodología
Después de realizar una breve limpieza de datos a la base, donde identificamos outliers y realizamos el respectivo tratamiento, seleccionamos únicamente una ruta (B12) para llevar a cabo la representación.

Primero, construimos el grafo bajo las siguientes condiciones:

Los vértices son las paradas de la ruta del bus.

Las flechas representan el recorrido realizado por el bus.

Las flechas estacionarias representan el tiempo de espera del bus en cada estación (para dejar y recoger pasajeros).

Posteriormente, calculamos los valores necesarios para construir el álgebra de configuración, incluyendo sus invariantes.

Finalmente, con base en esta información, incluimos algunas sugerencias de optimización para mejorar los tiempos de recorrido de la ruta.
---
# Material

1. PDF: Encontraran un archivo pdf con la explicación terica de la herramienta matemática que usamos para representar el problema de transporte seguido de unas breves partes del código de la implementacion de las ágebras de configuración para explicar en formato de presentación los resultados del código.
2. .ipynb: Este archivo contiene toda la implementación practica de lo mencionado anteriormente en formato notebook de python.


