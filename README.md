Glue Studio es una plataforma en la nube diseñada para optimizar y acelerar los procesos de validación y verificación de productos. Su principal objetivo es reducir los tiempos de comercialización mediante herramientas inteligentes que automatizan tareas clave, como la planificación de pruebas, la selección de instrumentos y el desarrollo de código de prueba.

La oportunidad de negocio que encontramos es que no se tiene cuantificado el beneficio que los clientes potencialmente podrian obtener al utilizar herramientas inteligentes que automatizan tareas clave, en este proyecto vamos a construir un modelo de medifición de benificios donde podemos cuantificar a los clientes los beneficios que podrian adquirir al implementar estas tecnologias en sus procesos operativos

El modelo de medición teórico de beneficios que estamos construyendo parte de segmentar las herramientas por tipo de beneficios y hemos encontrado 3 clasificaciones:

1.	Planificación de pruebas
2.	Selección de instrumentos
3.	Desarrollo de códigos de prueba

La primera parte consiste en determinar el tipo de data que necesitamos para elaborar los modelos, se anexa resumen de datos:


Datos relacionados con los beneficios del producto/servicio
•	Indicadores operativos previos y posteriores a la implementación:
Tiempo promedio de ejecución antes y después de la solución.
Recursos humanos y materiales utilizados antes y después.
•	Resultados financieros:
Costos directos e indirectos antes y después de adoptar las soluciones.
Incremento en ingresos atribuibles a la implementación.

Datos de uso del producto/servicio
•	Frecuencia de uso: Qué tan activamente se utiliza la solución.
•	Impacto directo: Casos de éxito específicos, mejora en tareas críticas o reducción de errores.

Datos de comparación y benchmarks
•	Estándares de la industria: Información que permita comparar el rendimiento del cliente con el de sus competidores o con benchmarks de la industria.
•	Historial de mejoras: Datos longitudinales que demuestren tendencias de optimización a lo largo del tiempo.
El status de datos es el siguiente:

Hay valores faltantes en el conjunto de datos? Si existen datos faltantes, sobre todo aquellos enfocados en valores de la industria e historicos de los clientes para generar los modelos, dentro de los procesos que vamos a llevar se tiene planificado hacer estas estimaciones y contar con historico de clientes, en proceso

 ¿Se pueden identificar patrones de ausencia? No, la información no tiene patrones de ausencia 

¿Cuáles son las estadísticas resumidas del conjunto de datos? Los datos con los que vamos a trabajar son cualitativos no se pueden cuantificar en resumenes estadisticos

¿Hay valores atípicos en el conjunto de datos? No se encuentra algun dato atípico

¿Cuál es la cardinalidad de las variables categóricas? La data que se analiza no tiene una medición categórica

¿Existen distribuciones sesgadas en el conjunto de datos? ¿Necesitamos aplicar alguna transformación no lineal? No aplica

¿Se identifican tendencias temporales? (En caso de que el conjunto incluya una dimensión de tiempo). No aplica

¿Hay correlación entre las variables dependientes e independientes? No aplica, en un momento el modelo nos deberia ayudar a encontrar causa / efecto, no correlación

¿Cómo se distribuyen los datos en función de diferentes categorías? (análisis bivariado) La data que se analiza no tiene una medición categórica

¿Se deberían normalizar las imágenes para visualizarlas mejor? No vamos a trabajar con imágenes

¿Hay desequilibrio en las clases de la variable objetivo? No tenemos una variable objetivo
