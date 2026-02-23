Entrega: Bubble Sort optimizado (marca de ultimo intercambio)

Contenido:
- src/BubbleSortBenchmark.java
  Ejecuta benchmarks y produce un CSV a stdout.

Requisitos:
- JDK 8+ (probado con Java 17 en el entorno de evaluacion).

Como compilar:
  javac -d out src/BubbleSortBenchmark.java

Como ejecutar (genera CSV):
  java -cp out BubbleSortBenchmark > resultados.csv

Columnas del CSV:
  algorithm,scenario,n,run,ns

Notas:
- Se incluyen dos algoritmos para comparar: basic y optimized.
- Escenarios: random, ascending, descending.
- Tamanos: 10, 100, 1000, 10000, 100000.
