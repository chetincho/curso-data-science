# Método drop_duplicates

En Pandas, drop_duplicates es un método que se utiliza para eliminar duplicados de un DataFrame. Este método pertenece a la clase DataFrame de Pandas y se utiliza para eliminar filas duplicadas basándose en los valores de las columnas especificadas.

La sintaxis típica de drop_duplicates es la siguiente:

DataFrame.drop_duplicates(subset=None, keep='first', inplace=False)

- subset: Especifica las columnas sobre las cuales se deben buscar duplicados. Si no se proporciona, se considerarán todas las columnas.
- keep: Especifica qué duplicado(s) mantener. Puede tomar los valores 'first' (mantener la primera ocurrencia), 'last' (mantener la última ocurrencia) o False (eliminar todas las ocurrencias).
- inplace: Si es True, modifica el DataFrame actual; si es False (valor predeterminado), devuelve un nuevo DataFrame con los duplicados eliminados.

En resumen, drop_duplicates es un método de Pandas que actúa sobre DataFrames y se utiliza para gestionar duplicados en los datos.

<br>
<br>
<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Martin_Ferraguti-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101010)](https://www.linkedin.com/in/martin-ferraguti/)
