# mongodb-design-nonsqlbooster

Este repositorio contiene la tarea de bases de datos no relacionales del Máster en Big Data y Business Analytics.

## ¿Qué son las bases de datos NoSQL?

NoSQL abarca una amplia variedad de tecnologías de bases de datos diferentes que se desarrollaron en respuesta a las demandas presentadas en la construcción de aplicaciones modernas:
Los desarrolladores están trabajando con aplicaciones que crean volúmenes masivos de nuevos tipos de datos que
cambian rápidamente: datos estructurados, semiestructurados, no estructurados y polimórﬁcos.
Se acabó el ciclo de desarrollo de la cascada de doce a dieciocho meses. Ahora los equipos pequeños trabajan en sprints
ágiles, iterando rápidamente y presionando el código cada semana o dos, algunas incluso varias veces al día.
Las aplicaciones que una vez sirvieron a una audiencia limitada ahora se entregan como servicios que deben estar siempre
encendidos, accesibles desde muchos dispositivos diferentes y escalados globalmente a millones de usuarios.
Las organizaciones ahora están recurriendo a arquitecturas de escalamiento horizontal que utilizan software de código
abierto, servidores de productos básicos y computación en la nube en lugar de grandes servidores monolíticos e
infraestructura de almacenamiento.
Las bases de datos relacionales no se diseñaron para hacer frente a los desafíos de escala y agilidad que enfrentan las
aplicaciones modernas, ni se crearon para aprovechar el almacenamiento de productos básicos y la capacidad de
procesamiento disponible en la actualidad.

## ¿Qué es MongoDB?

MongoDB (del inglés humongous, "enorme") es un sistema de base de datos NoSQL orientado a documentos de código abierto y escrito en C++, que en lugar de guardar los datos en tablas lo hace en estructuras de datos BSON (similar a JSON) con un esquema dinámico. Al ser un proyecto de código abierto, sus binarios están disponibles para los sistemas operativos Windows, GNU/Linux, OS X y Solaris y es usado en múltiples proyectos o implementaciones en empresas.

## Características principales:

- **Consultas ad hoc**. Con MongoDb podemos realizar todo tipo de consultas. Podemos hacer búsqueda por campos, consultas de rangos y expresiones regulares. Además, estas consultas pueden devolver un campo específico del documento, pero también puede ser una función JavaScript definida por el usuario.
Indexación. El concepto de índices en MongoDB es similar al empleado en bases de datos relacionales, con la diferencia de que cualquier campo documentado puede ser indexado y añadir múltiples índices secundarios.

- **Replicación**. Del mismo modo, la replicación es un proceso básico en la gestión de bases de datos. MongoDB soporta el tipo de replicación primario-secundario. De este modo, mientras podemos realizar consultas con el primario, el secundario actúa como réplica de datos en solo lectura a modo copia de seguridad con la particularidad de que los nodos secundarios tienen la habilidad de poder elegir un nuevo primario en caso de que el primario actual deje de responder.

- **Balanceo de carga.** Resulta muy interesante cómo MongoDB puede escalar la carga de trabajo. MongoDB tiene la capacidad de ejecutarse de manera simultánea en múltiples servidores, ofreciendo un balanceo de carga o servicio de replicación de datos, de modo que podemos mantener el sistema funcionando en caso de un fallo del hardware.
 
-**Almacenamiento de archivos.** Aprovechando la capacidad de MongoDB para el balanceo de carga y la replicación de datos, Mongo puede ser utilizado también como un sistema de archivos. Esta funcionalidad, llamada GridFS e incluida en la distribución oficial, permite manipular archivos y contenido.
Ejecución de JavaScript del lado del servidor. MongoDB tiene la capacidad de realizar consultas utilizando JavaScript, haciendo que estas sean enviadas directamente a la base de datos para ser ejecutadas.

## ¿Cúal es la IDE utilizada en el proyecto?
La IDE o  cliente utilizado en este proyecto ha sido NoSQLBooster (https://nosqlbooster.com/home).

## ¿Cuál es el proyecto a realizar?
Sobre un Dataset de datos dado llamado  *Movies*, hay que hacer los siguientes pasos:
- Cargar / Importar dataset de  *Movies*.
- 23 Ejercicios sobre inserción, actualización, proyección, ﬁltrado y el pipeline de agregación.
- 3 Ejercicios Libres sobre el pipeline de agregación.
- Entregar ﬁchero PDF con las querys de todos los ejercicios mostrando una captura de pantalla con los resultados.

