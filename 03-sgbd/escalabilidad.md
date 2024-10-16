# Ejercicio 1
*¿Qué es la escalabilidad vertical y escalabilidad horizontal? ¿Qué SGBD permiten un mejor escalado horizontal?*


## Escalabilidad Vertical
La escalabilidad vertical implica aumentar la capacidad de un solo servidor mejorando sus recursos, como añadir más CPU, RAM o almacenamiento. Es más sencilla de implementar, ya que no requiere cambios significativos en la arquitectura, pero tiene un límite físico y puede ser costosa.

## Escalabilidad Horizontal
La escalabilidad horizontal consiste en añadir más servidores al sistema para manejar la carga de trabajo. Esto permite distribuir el tráfico y mejorar el rendimiento de manera más efectiva. Es más compleja de implementar, ya que requiere que la aplicación y la base de datos soporten la distribución de datos y operaciones.

## SGBD que permiten mejor escalado horizontal

Cassandra: Diseñado para manejar grandes volúmenes de datos en múltiples servidores sin un punto único de fallo.
MongoDB: Ofrece particionamiento (sharding) que permite distribuir datos en múltiples nodos.
CockroachDB: Es un SGBD SQL que permite la replicación y particionamiento automático de datos, optimizando la escalabilidad horizontal.
Amazon DynamoDB: Un servicio de base de datos NoSQL que escala automáticamente según la demanda.
Elasticsearch: Ideal para búsquedas y análisis de datos en tiempo real, permite distribuir índices entre nodos.
