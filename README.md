# Ventas_Cantidades_Montos
Ventas de diferentes tiendas en cantidades (unidades) y montos ($), y analizar comportamiento
Comportamiento de las ventas por tiendas
% de Ventas por Producto

En la empresa hay diferentes tipos de clientes, en donde la mayoría son los "Consumidores Finales", es decir, personas que realizan la copia para su propio consumo (y el de sus familiares cercanos), y por lo general es para consumir en el corto plazo. En contraparte, los clientes con menos compras son los llamados "Gran Volumen", es decir, clientes que compran en muy grandes cantidades:

![Gráfico de Ventas por Tipo de Cliente](https://github.com/vittoriadelsignore/Ventas_Cantidades_Montos/blob/master/Cantidad%20por%20tipos%20de%20clientes.png)

Las ventas en cantidad se distribuyen en las diferentes tiendas de forma diferente, siendo la tienda Nido la que lidera el volumen acumulado, seguida por Chaco y Flor:

![Gráfico de Ventas por Tienda](https://github.com/vittoriadelsignore/Ventas_Cantidades_Montos/blob/master/Venta%20por%20Tienda.png)

Evaluemos por medio de una gráfica BoxPlot el comportamiento de las ventas por producto, donde lo más vendidos son las cervezas y refrescos, y los alimentos básicos; en donde hay clientes que hacen compras de grandes cantidades, por eso hay múltiples valores de outliers:

![Gráfico de Ventas por Producto](https://github.com/vittoriadelsignore/Ventas_Cantidades_Montos/blob/master/Boxplot%20Producto.png)

Podemos encontrar, como es de esperar, relación entre las 2 variables principales de este análisis, es decir: cantidad (unidades) y ventas ($), lo cual se ve plasmado en el siguiente gráfico, que expresa que a mayor cantidad de productos se venden, entonces hay mayor venta a nivel monetario:

![Gráfico de Relación Cantidad y Ventas](https://github.com/vittoriadelsignore/Ventas_Cantidades_Montos/blob/master/Cantidad%20vs%20Venta%20Feb21.png)

Ahora abrimos ese gráfico por tipo de cliente, en donde se ve que el grupo que tiene mayor cantidad de ventas, que es el grupo formado por consumidores finales, es aquel que también tiene más ventas en termino monetario:

![Gráfico de Relación Cantidad y Ventas por tipo de cliente](https://github.com/vittoriadelsignore/Ventas_Cantidades_Montos/blob/master/Cantidad%20vs%20Venta%20Feb21%20por%20tipo%20cliente.png)

Si nos centramos en Cervezas y Refrescos, podemos ver que la venta se concentra en la tienda Noto:

![Gráfico de Cervezas y Refrescos por Tienda](https://github.com/vittoriadelsignore/Ventas_Cantidades_Montos/blob/master/Boxplot%20Cervezas%20y%20Refrescos.png)
