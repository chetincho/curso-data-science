# Introduccion a Pandas

## Comencemos por definir qué es Pandas
Pandas es una biblioteca de código abierto para el lenguaje de programación Python la cual proporciona estructuras de datos de alto rendimiento y fáciles de usar, así como herramientas de análisis de datos. Se utiliza para manipulación y limpieza de datos, así como para realizar operaciones de análisis de datos en conjuntos de datos tabulares.

Las dos estructuras de datos principales en Pandas son:
- Series: Es un array unidimensional etiquetado capaz de contener cualquier tipo de datos. Se puede pensar en un array como una columna de una hoja de cálculo o una serie temporal. Por ejemplo, este es un array con el top 10 de los paises con mas población del mundo.

|-------------------|
| País              |
|-------------------|
| China             |
| India             |
| Estados Unidos    |
| Indonesia         |
| Pakistán          |
| Brasil            |
| Nigeria           |
| Bangladesh        |
| Rusia             |
| México            |
|-------------------|

- DataFrame: Es una estructura de datos bidimensional similar a una tabla de base de datos o una hoja de cálculo de Excel. Se puede ver como una colección de Series, donde cada Serie es una columna. Siguiendo con el ejemplo anterior este es un ejemplo de DataFrame donde ademas de los países ahora se incluye la poblacion en millones de habitantes.

+-------------------+----------------------+
| País              | Población (millones) |
+-------------------+----------------------+
| China             | 1441M                |
| India             | 1393M                |
| Estados Unidos    | 332M                 |
| Indonesia         | 276M                 |
| Pakistán          | 225M                 |
| Brasil            | 213M                 |
| Nigeria           | 211M                 |
| Bangladesh        | 166M                 |
| Rusia             | 145M                 |
| México            | 130M                 |
+-------------------+----------------------+

Pandas es ampliamente utilizado en ciencia de datos, análisis financiero, inteligencia empresarial y otros campos donde se trabaja con datos tabulares. Facilita la carga, limpieza, manipulación y análisis de datos de manera eficiente.

### Pandas vs Excel
A continuación estas diferencias resumen las características clave de la libería Pandas de Python y Microsoft Excel, resaltando sus fortalezas y limitaciones en diversos aspectos.

| Característica                | Pandas (Python)                                  | Microsoft Excel                                |
| ----------------------------- | ----------------------------------------------- | ----------------------------------------------- |
| **Tipo de Herramienta**        | Librería de programación para análisis de datos  | Software de hoja de cálculo con interfaz gráfica|
| **Lenguaje de Programación**   | Python                                          | Basado en fórmulas y macros                     |
| **Flexibilidad**               | Programación y análisis de datos avanzado        | Interfaz gráfica fácil de usar                 |
| **Capacidad de Automatización**| Altamente automatizable mediante scripts Python | Automatización a través de macros y VBA         |
| **Manejo de Grandes Conjuntos de Datos** | Eficiente para grandes volúmenes de datos   | Puede volverse lento con conjuntos de datos masivos|
| **Funciones de Análisis Estadístico** | Ofrece una amplia variedad de funciones estadísticas | Proporciona funciones estadísticas básicas      |
| **Integración con Otras Bibliotecas** | Puede integrarse fácilmente con NumPy, SciPy, etc. | Limitada integración con otras bibliotecas       |
| **Licencia**                  | Código abierto (licencia BSD)                  | Software propietario (licencia comercial)       |
| **Compatibilidad Plataforma** | Multiplataforma (Windows, macOS, Linux)        | Principalmente para Windows, disponible en macOS |
| **Escalabilidad**             | Escalable y utilizado en entornos de producción | Mejor para tareas individuales y pequeñas empresas|


Antes de ingresar de lleno en el mundo de Pandas debemos comprender primero qué es un DataFrame:

Un DataFrame en Pandas es esencialmente una estructura de datos bidimensional, similar a una tabla en una base de datos o una hoja de cálculo de Excel. Puedes pensar en un DataFrame como una estructura de datos tabular con filas y columnas etiquetadas.

Las filas representan observaciones o registros, mientras que las columnas representan variables o atributos.

En un DataFrame, cada columna puede contener diferentes tipos de datos, como enteros, flotantes, cadenas, etc. Además, los DataFrames en Pandas proporcionan una amplia gama de funciones y métodos para realizar operaciones de manipulación, filtrado, agregación y análisis de datos de manera eficiente.

En resumen, un DataFrame en Pandas es una herramienta poderosa para organizar y manipular datos tabulares de manera estructurada y eficiente en el entorno de programación en Python.