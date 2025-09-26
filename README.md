[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/7IRjtlNy)
# Presentación final del curso de Programación I

Este repositorio tiene como propósito servir de contenedor para los archivos de la presentación final del curso. Se deben guardar todos los archivos utilizados para la presentación (vea las condiciones de entrega más adelante). 

*Banco de Guatemala*  
*Maestría en Economía y Finanzas Aplicadas*  
*Programación I*  
*Fecha: Septiembre de 2025*

## Objetivos

El presente proyecto tiene como objetivo que el estudiante conozca nuevos paquetes del lenguaje de Python o que desarrolle lógica de programación necesaria para realizar alguna aplicación interesante utilizando programación científica o métodos de simulación de Monte Carlo. 


## Rúbrica de evaluación 

| Aspecto a evaluar                                                                             |  Punteo |
|:----------------------------------------------------------------------------------------------|--------:|
| Definición y delimitación del proyecto                                                        |      10 |
| El proyecto requiere conocimientos/esfuerzo adicional al ganado/realizado en el curso         |      10 |
| Participantes del grupo colaboraron cada uno con confirmaciones (*commits*) en el repositorio |      10 |
| Exposición clara, interacción con el público y manejo de los límites de tiempo (5-10 minutos) |      20 |
| El proyecto utiliza conceptos, paquetes, algoritmos o herramientas no vistas en clase         |      20 |
| Dominio del código y manejo de preguntas de los estudiantes o del profesor                    |      30 |
| **Total**                                                                                     | **100** |


## Formato de entrega 

- El proyecto debe entregarse utilizando la plataforma de GitHub, a través de las confirmaciones (*commits*) necesarios por los miembros de cada equipo. 
  - Tomar en cuenta que el repositorio será público. Evitar compartir datos personales, contraseñas u otra información sensible. Los repositorios pueden ser visitados nuevamente en el sitio de la organización `PES-BG-2025` para futuras consultas de parte de todos los estudiantes. 
- Los archivos finales del proyecto se pueden guardar en el directorio raíz del repositorio utilizando cualquier estructura deseada. Sin embargo, si se utilizan archivos de prueba que puedan servir como muestra del procedimiento realizado, pero que no formen parte del proyecto final, se deben guardar en un directorio especial denominado `deprecated`. 
- No cargar archivos al repositorio que sean demasiado grandes (>10MB) como fotografías o vídeos. Utilizar recursos o plataformas web específicamente diseñadas para estos propósitos. La única excepción a esta regla es para el archivo de presentación. 
- Un archivo de presentación es opcional. Si se utiliza una presentación en PowerPoint o PDF, esta debe ser adjuntada en la raíz del proyecto. 
- Al final de la presentación, se dará un tiempo para realizar preguntas, tanto del profesor o de los estudiantes.
- Atender a otras indicaciones adicionales por parte del instructor al inicio y durante la presentación. 
- La fecha de entrega máxima para realizar las confirmaciones será el **jueves 25 de septiembre de 2025 a las 23:59 horas**.

- ## Uso de inteligencia artificial

- En cada presentación, los profesores medirán un índice de uso de inteligencia artifical (IA) de 0 a 10 con base en el dominio del código y preguntas que puedan surgir. 
- Si se detecta el uso de ChatGPT o chatbots para realizar partes significativas del código, se aplicará un factor de descuento con base en este índice:

| Índice de uso (0 - 10)    |  % descuento |
|:-------|--------:|
| 0 - 3  |      0% |
| 4 - 6  |     30% |
| 7 - 8  |     60% |
| 9 - 10 |     90% |

**El uso de IA está permitido, pero su mal uso está prohibido.**

- Ejemplos de buen uso:
  - Explicación de piezas de código o sentencias del lenguaje.
  - Depuración de errores.
  - Elaboración de casos de pruebas.
  - Generación de ideas o mejoras en un programa.
  - Elaborar los docstrings de las funciones.
  - Consulta sobre flujos de trabajo en VSCode, GitHub, etc.
  - Pedir ejemplos sobre cómo utilizar una librería en Python. 
 
- Ejemplos de mal uso: 
  - Pedir a los chatbots que elaboren funciones o clases completas.
  - No entender el código brindado por los chatbots (uso ciego).
  - No entender la organización del código porque todo fue elaborado por el chatbot.


## Descripción del proyecto "Messi Code"

**Justificación**  
A lo largo de los años, distintos estudios han tratado de predecir y estimar cuántos sobres y cuál sería el costo aproximado para completar un álbum de estampitas. En este proyecto se presentan dos escenarios que buscan aproximarse a la realidad, basándonos en las variables mencionadas.

### Escenario 1
Un coleccionista quiere llenar su álbum bajo los siguientes supuestos:

- 1 álbum  
- 670 estampitas  
- Cada sobre contiene 5 estampitas **sin repetidas dentro del mismo sobre**  
- Todas las estampitas tienen la misma probabilidad de aparecer (distribución uniforme)  
- Costo por sobre: Q6.75  

Con estos supuestos, se realiza una simulación de Monte Carlo con n repeticiones (definidas por el usuario).  
Resultados esperados: número promedio de sobres necesarios para llenar el álbum, costo total promedio y cantidad promedio de estampitas repetidas obtenidas durante el proceso.

### Escenario 2
Se aproxima una situación más realista con dos coleccionistas que desean llenar el mismo álbum al mismo tiempo y están dispuestos a intercambiar repetidas, bajo los siguientes supuestos:

- Todas las estampitas tienen la misma probabilidad de aparecer (distribución uniforme).  
- Ambos coleccionistas comienzan al mismo tiempo.  
- Ambos compran un sobre simultáneamente.  
- Tras cada compra, actualizan sus álbumes.  
- Las estampitas duplicadas pasan a la lista de intercambio de cada coleccionista.  
- El intercambio sucede únicamente si ambos tienen la misma estampita para intercambiar (1×1).

Igual que en el primer escenario, mediante simulación de Monte Carlo se obtiene el número promedio de sobres, el costo promedio y la cantidad promedio de estampitas repetidas.
