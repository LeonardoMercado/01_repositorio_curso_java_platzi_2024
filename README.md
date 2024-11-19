# 01_repositorio_curso_java_platzi_2024

Repositorio para el manejo de los diferentes ejercicios del curso de java 21 en platzi, 2024

# Comparación de versiones de Java: 8, 11 y 21

| **Versión** | **Fecha de Lanzamiento** | **Cambios Importantes**                                                                                      |
|-------------|--------------------------|-------------------------------------------------------------------------------------------------------------|
| **Java 8**  | Marzo 2014               | - Introducción de **Expresiones Lambda** y **Streams** (programación funcional).                           |
|             |                          | - **Interfaz funcional** (`@FunctionalInterface`) y métodos por defecto en interfaces.                     |
|             |                          | - API de fecha y hora mejorada (**java.time**).                                                            |
|             |                          | - Anotaciones en tipos (`@NonNull`, etc.).                                                                 |
|             |                          | - Mejoras en JavaFX (ahora separado del JDK en versiones posteriores).                                     |
|             |                          | - Nashorn: Motor de JavaScript.                                                                            |
| **Java 11** | Septiembre 2018          | - Eliminación de APIs y herramientas obsoletas: **Nashorn** y **JavaFX** se separaron del JDK.             |
|             |                          | - **Inferencia de tipos** en variables locales con `var`.                                                  |
|             |                          | - Nuevos métodos en `String`: `lines()`, `strip()`, `repeat()`.                                            |
|             |                          | - Métodos convenientes en colecciones (`toArray(IntFunction)` y `Collectors.toUnmodifiableList`).          |
|             |                          | - **HttpClient API** para manejar solicitudes HTTP/2 y WebSockets.                                        |
|             |                          | - Ejecución directa de scripts `.java` sin necesidad de compilarlos (`java HelloWorld.java`).              |
| **Java 21** | Septiembre 2023          | - **Patrones en switch** (`switch` mejorado para soportar patrones).                                       |
|             |                          | - **Record patterns** para desestructuración más sencilla en clases `record`.                              |
|             |                          | - **Scoped values**: Alternativa ligera a `ThreadLocal` para valores inmutables.                          |
|             |                          | - **Sequenced Collections**: Nuevas interfaces (`SequencedSet`, `SequencedMap`) para estructuras ordenadas.|
|             |                          | - Mejoras de rendimiento en la JVM gracias al **Proyecto Loom**: Soporte para **hilos virtuales**.         |
|             |                          | - Extensión de programación funcional: `Stream.mapMulti()`.                                               |
|             |                          | - Nuevas funciones de seguridad, como restricciones para **JAR no confiables** y más opciones de cifrado. |

## Resumen de cambios clave
1. **De Java 8 a Java 11**:
   - Enfoque en limpiar el JDK (herramientas obsoletas eliminadas).
   - Inclusión de características modernas como `var` y nuevos métodos convenientes en APIs existentes.
   - Adopción de estándares más recientes como HTTP/2.

2. **De Java 11 a Java 21**:
   - Evolución significativa del lenguaje con patrones (`switch`, `record patterns`).
   - Cambios orientados a la eficiencia y simplificación de programación concurrente con los hilos virtuales.
   - Adiciones orientadas a colecciones y estructuras de datos más flexibles.

## Conclusión
Java 21 representa un salto importante, especialmente por las mejoras en programación funcional, estructuras de datos y concurrencia. Además, introduce herramientas modernas que facilitan el desarrollo y la productividad.

