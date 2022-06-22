# Prueba PHP

Generar un gráfico histórico del índice pobreza en el Perú.

1. Obtener información de PIP del API del Banco Mundial de Perú entre los años 1995 y 2020.

   Eg.
   
    Si queremos obtener la información del año 2019 deberiamos usar la siguiente url vía get:

    https://api.worldbank.org/pip/v1/pip?country=PER&year=2019

    Se obtendrá un json de la siguiente forma, de este listado de parámetros usar el campo "headcount"

    ![data](https://raw.githubusercontent.com/fragotesac/php-interview-test/master/data.png)

2. Usar la librería https://www.highcharts.com/demo para generar el gráfico.


Imagen de referencia:

![graph](https://raw.githubusercontent.com/fragotesac/php-interview-test/master/graph.png)


