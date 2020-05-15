Ruta óptima para los colaboradores de la fuerza de ventas
==============================

### Sesión de kick off. 20 de abril de 2020

El equipo 1 y 4 se reunió para definir el problema a resolver, la forma de trabajo del equipo y 
el objetivo del problema: encontar la ruta de los colaboradores que minimice la distancia recorrida.

+ Se construye el archivo con raw data que servirá para la creación de la base de datos.

+ Los algoritmos a revisar son: Particule Swarm Optimizacion (PS) y Simulated Annealing (SA).

+ Equipo de trabajo

La división del equipo de trabajo se muestra a continuación:

| Alumno | Equipo |
|--------|--------|
| Marco  | PS |
| Laura | PS |
| Diego | PS |
| Miguel | SA |
| Paola | SA |
| Ana   | SA |


### Milestone 1. Fin: 09 de mayo de 2020

El objetivo principal de este milestone fue tener el desarrollo de los algoritmos en Python. Para ello, se llevaron a cabo las siguientes actividades: 

1. Entendimiento del algoritmo asignado 

  a. Entendimiento general de Travelling Salesman Problem y diferencia con los ciclos hamiltonianos
  b. Revisión de literatura para los algoritmos de: Simulated Annealing y Particle Swarm Optimization
  c. El equipo de PS le explicó al equipo de SA el algoritmo y viceversa
  
2. Desarrollo de los algoritmos. Se acuerda tener un archivo Utileria.py con funciones útiles para los algoritmos. 

3. Prueba de los algoritmos

El detalle de las activades realizadas por cada integrante del equipo se muestran a continuación: 

Diego: entendimiento de particle swarm y replicación de un algoritmo para entendimiento de cómo se puede 
adaptar el algoritmo al problema de travellers salesman person. El notebook con este algoritmo está disponible para su consulta en LINK.

Lau: entendimiento y explicación de la parte matemática del algoritmo de Particle Swarm y validación de parámetros del algoritmo 

Marco: desarrolló la función para el cálculo de distancias entre puntos y el algoritmo de Particle Swarm

En python existe una función para el cálculo de Simulated Annealing y una forma de paralelizar el algoritmo es a través de una metodología llamada
Simulated Annealing. Bajo este contexto, Pao y Miguel trabajaron en lo siguiente: 

Pao: revisó el paper de Coupled Simulated Annealing y construyó la primera iteración del docker 

Miguel: construyó una función para la transformación de los datos de Simulated Annealing y revisó 
la documentación sobre los parámetros que tiene la función

Ana: construyó una función para la transformación de los datos de Particle Swarm y ejecutó pruebas con 
ambos algoritimos para evaluar su desempeño y comparar las mejores rutas

	
El 9 de mayo se tuvo la reunión con Erick y se llegan a los siguientes acuerdos: 
+ Paralelizar los datos en lugar del algoritmo. Se utilizará dask para esta tarea
+ Construir una base de datos con raw data y las salidas de la rutas
+ Desarrollar un dashboard para la visualización de las rutas
