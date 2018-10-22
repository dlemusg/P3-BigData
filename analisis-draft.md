# PROYECTO 3 - BIGDATA
## Curso ST0263 Tópicos Especiales en Telematica
## Universidad EAFIT
## 2018-2

## Estudiantes:
* David Felipe Lemus Giraldo
* Juan Camilo Rodriguez Montoya

## Problema seleccionado ##

Realizar una prueba de concepto o demo sobre Data Streaming desde Twitter utilizando una de las siguientes tecnologías: Kafka, Storm, Flink o Flume.

## Streaming Data 

La definicion mas acertada Streaming Data para nostros es la de amazon AWS:

 "Los datos de streaming son datos que se generan constantemente a partir de miles de fuentes de datos, que normalmente envían los registros de datos simultáneamente en conjuntos de tamaño pequeño (varios kilobytes). Los datos de streaming incluyen diversos tipos de datos, como archivos de registros generados por los clientes que utilizan sus aplicaciones móviles o web, compras electrónicas, actividades de los jugadores en un juego, información de redes sociales, operaciones bursátiles o servicios geoespaciales, así como telemetría de dispositivos conectados o instrumentación en centros de datos." 


Estos datos son procesados secuencial y gradualmente registro por registro o en ventanas de tiempo graduales. Son utilizados para en analisis, correlaciones, agregaciones y muestreo. 

El analisis de esta informacion aporta a las empresas ventajas en el conocimiento de los aspectos de negocio y actividades de los cliente de forma rapida ante cualquier situación.


## Ejemplos de Streaming Data

* Sensores de los vehiculos de transporte envian datos a una app de streaming. Esta aplicacion se encarga de supervisar el rendimiento, dectetar fallos y envía los cambios automaticamente, esto evita el tiempo de inactivada del equipo.

* Empresa de energia solar debe mantener suministro constante a sus cliente. Implementó una app de streaming que supervisa los paneles y programa el servicio en tiempo real para asi minimizar los periodos de escaso suministro y por tanto sanciones economicas.

* Empresa de juegos en linea recopila datos de las interacciones de los jugadores con este. Posterior, analiza los datos en tiempo real, ofrece incentivos y experiencias dinamicas que involucren jugadores. 


## Kafka

Es una platadorma "distributed streaming" capaz de manejar millones de eventos al dia. Fue concebida iicalmente como una cola de mensajeria, se basa en la abstraccion de un registro de confirmación distribuido. Desde su creación e inaguración por linkedIn ha evolucionado rapidamente a una plataforma de transmisión completa. 


## Referencias

What is Apache Kafka®? https://www.confluent.io/what-is-apache-kafka/
¿Qué son los datos de streaming? https://aws.amazon.com/es/streaming-data/
