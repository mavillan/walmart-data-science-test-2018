# Walmart Chile data science test 2018
Desafío para postulantes a prácticas de data science en Walmart Chile 2018


En el archivo `/data/data_practica.zip` encontrarás una muestra de las transacciones que registramos todos los días. Puedes ver una muestra de los datos a continuación:

|Fecha|Cliente|Boleta|Producto|Cantidad|Venta|Costo|
|--- |--- |--- |--- |--- |--- |--- |
|1/2/17|1|1|1|1|1390|1294|
|1/2/17|1|1|2|1|900|802|
|1/2/17|1|1|3|1|890|813|
|1/2/17|1|1|4|1|2490|2432|
|1/2/17|1|1|5|1|1890|1607|
|1/2/17|1|1|6|1|1440|1250|
|1/2/17|1|1|7|1|740|703|
|1/2/17|2|2|8|1|1450|1412|
|1/2/17|2|2|9|1|2990|2602|
|1/2/17|3|3|10|1|690|646|
|1/2/17|3|3|11|1|1850|1819|
|1/2/17|3|3|12|1|690|608|

El archivo tiene `2.569.612` filas, donde cada una corresponde a un producto de una boleta de un cliente. Para cada producto 
incluimos además: (1) la cantidad de unidades vendidas, (2) la venta total de ese producto en la boleta, es decir, 
`precio*cantidad`, y (3) el costo (también total de ese producto en la boleta, no unitario). El costo (simulado para este 
ejercicio), es el precio al cual Walmart compra el producto, por lo tanto, la utilidad del producto en esa compra puede ser 
calculada como `Venta-Costo`.

Te invitamos a responder lo siguiente:

1. Proponga una clusterización de clientes en base al registro transaccional. 
2. Determine cuál es el clúster de mejores clientes. 
3. Para el clúster anterior, encuentre cuáles son los 15 productos más relevantes. 

Los preguntas anteriores son bastante abiertas, esperamos que preguntas como: ¿Qué variables construir para la clusterización?, ¿Cómo 
normalizarlas?, ¿Cómo defino a un "buen" cliente, es acaso el que más compra o el que más veces compra? ¿Cómo defino 
la relevancia de un producto?, etc.

El formato de entrega puede ser **Python Notebook** o **R Markdown**. El Plazo límite de entrega: **Miércoles 19 de diciembre, 
al mediodía**. Se recomienda **clonar** o hacer un **fork** de este repositorio, y realizar su entrega por **Github**. También 
puedes hacer tu entrega enviando un correo a `sebastian.torres@walmart.com`, también a este correo puedes hacer preguntas respecto del proceso.

Con este ejercicio no solo buscamos evaluar tu capacidad de trabajar con un lenguaje de programación, y de librerías básicas para 
Data Science. Si no que también la habilidad de encontrar problemas, proponer soluciones, y comunicarlas de manera efectiva. 
Aprovecha esta oportunidad! Éxito!
