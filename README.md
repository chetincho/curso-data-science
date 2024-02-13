# Introduccion a Pandas

### 1000 Introduccion:
Vemos conceptos básicos, definición de un DataFrame, consultas básicas y sus atributos, funciones y métodos mas básicos.

- 1000_introduccion.ipynb: Importamos las librerías Pandas y Numpy y se exploran las distintas formas en las cuales podemos crear un DataFrame.

- 1001_introduccion.ipynb: Creamos un DataFrame a partir de un csv y exploramos las formas básicas para mostrar su contenido.

- 1002_introduccion.ipynb: Definimos los conceptos `Atributos`, `Funciones` y `Métodos`

### Ruta de Aprendizaje


- [ ] Tratamiento de la información duplicada: Método [drop_duplicates](https://github.com/chetincho/curso-data-science/blob/main/metodo_drop_duplicates.md)
Archivo: duplicados.ipynb








<p>
### Buenas Prácticas
0- Documentar siempre es bueno, no solo para darle mantenimiento al código, sino también para poder comportirlo y que este sea comprendido de forma rápida y sencilla por el resto. <br>
1 - Importamos las librerías que vamos a utilizar. <br>
2 - Ahora continuamos con la carga del dataframe. <br>
3 - Comienza lo bueno, es momento del "Data Analysis" o Análisis exploratorio de datos. <br>
3.1 - 
3.2 - 
3.3 - 
3.4 - 
<p>










1- Luego de cargar el dataset utilizar el método `varDataFrame.info()` para conocer:
* Si existen o no valores nulos y formular una estrategia para su tratamiento.
* El tipo de dato de cada columna y analizar si corresponden o no transformaciones.

Ej: La columna "Precio", "Cantidad", etc, etc son de tipo object cuando en realidad deberian ser de tipo float.

<class 'pandas.core.frame.DataFrame'>
RangeIndex: 1274 entries, 0 to 1273
Data columns (total 20 columns):
 #   Column                                Non-Null Count  Dtype  
---  ------                                --------------  -----  
 0   NEGOCIO                               1274 non-null   object 
 1   CAJA                                  1274 non-null   object 
...
...
 9   Precio                                1119 non-null   object 
 10  Cantidad                              1119 non-null   object 
 11  Tot % bonif.                          1119 non-null   object 
 12  Total Facturado                       1215 non-null   object 
 13  Hora de Venta                         1119 non-null   object 
 ...
 ...
dtypes: float64(1), int64(2), object(17)
memory usage: 199.2+ KB

Con la funcion `nombre_dataframe.dtypes` obtengo un resultado similar, solo que se limita a mostrar el tipo de cada columna

NEGOCIO                                  object
CAJA                                     object
...
...
Precio                                   object
Cantidad                                 object
Tot % bonif.                             object
Total Facturado                          object
...
...
dtype: object


<br>
<br>
<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Martin_Ferraguti-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101010)](https://www.linkedin.com/in/martin-ferraguti/)
