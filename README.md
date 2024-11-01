# Spark RDD - Transformaciones y Acciones

Este repositorio proporciona ejemplos básicos de transformaciones y acciones en Apache Spark usando RDDs (Resilient Distributed Datasets). Cada transformación y acción tiene su propio archivo en las carpetas `transformaciones/` y `accciones/`.

## Contenidos
- **Transformaciones**: Operaciones que crean un nuevo RDD a partir de uno existente.
- **Acciones**: Operaciones que ejecutan el cálculo en el RDD y devuelven un valor al driver.

## Requisitos
- Apache Spark
- Python o Scala

## Ejecución
Para ejecutar cada ejemplo, asegúrate de tener Apache Spark instalado y ejecuta cada archivo `.py` desde la línea de comandos.

## Transformaciones
- [map.py](transformaciones/map.py): Ejemplo de transformación `map`, que aplica una función a cada elemento del RDD.
- [filter.py](transformaciones/filter.py): Ejemplo de transformación `filter`, que filtra elementos según una condición.
- [flatMap.py](transformations/flatMap.py): Ejemplo de transformación `flatMap`, que divide cada elemento en múltiples elementos.



