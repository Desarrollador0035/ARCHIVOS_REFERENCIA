<p>Sql siempre nos devuelve tablas virtuales</p>
### 01-CONSULTAS SELECT
<p>SELECT column,another_column, FROM mytable;</p>
<p>La sintaxis muestra una consulta de conjunto bidemensional de filas y columnas, una copia de la tabla pero solo con columnas
que solicitamos</p>
<br>
<br> 

## 02-QUERIES WITH CONSTRAINTS(PT.1) CONSULTAS CON RESTRICCIONES
**WHERE**: Se aplica a cada fila de datos verificando valores de columna especificos para determinar si debe incluirse o no, se utiliza para filtrar registros
, extrare solo aquellos registros que cumplen una condición especifica.
<br>
*Sintaxis* : SELECT column1,column2 FROM table_name WHERE condition;
<br>
<p>Selecciona todos los clientes de MEXICO</p>
<br>

**SELECT * FROM Customers WHERE Country = "Mexico";**
<br>

**SELECT * FROM Customers WHERE CustomersID = 1;**

<table>
  <tr>
    <th>Operador</th>
    <th>Codicion</th>
    <th>SQL Ejemplo</th>
  </tr>
  <tr>
    <td>=,!=,<,<=</td>
    <td>Operadores numericos Estandar</td>
    <td>col_name 1=4</td>
  </tr>
      <tr>
        <td>BETWEEN, AND</td>
        <td>Buscar el rango en 2 valores(inClusive)</td>
        <td>col_name BETWEEN 1.5 AND 10.5</td>
      </tr>
    <tr>
      <td>NOT BETWEEN, AND</td>
      
    </tr>
      
</table>





