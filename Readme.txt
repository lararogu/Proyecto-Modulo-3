1. Título: Dashboard Excel  (Modulo 3)

2. Descripción del Proyecto
Este proyecto realiza un análisis exploratorio de los datos de una cadena de supermercados durante los primeros 3 meses de 2019.
Los datos disponibles de este supermercado son:
Invoice id: Numero identificativo de la factura generada al comprador
Branch: sucursal/sede del supermercado (se identifican como A, B and C).
City: localización de cada sede del supermercado
Customer type: tipo de cliente (miembro del supermercado o cliente normal sin tarjeta de cliente)
Gender: genero del cliente
Product line: linea de producto - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel
Unit price: precio por unidad de producto (en dólares americanos)
Quantity: cantidad total de productos adquiridos por cada compra
Tax: tasa/iva del 5% aplicado a cada compra
Total: precio total
Date: fecha de la compra
Time: hora de la compra
Payment: método de pago utilizado -  Cash, Credit card and Ewallet)
Rating: satisfacción del cliente por cada compra (de 0 a 100)

3. Estructura del Proyecto
Los ficheros incluidos en este proyecto son:
Archivo Excel con los datos fuente. (supermarket_sales csv)
Archivo Excel incluyendo los datos analizados y el dashboard. (supermarket_sales)
Readme

4. Informe explicativo del análisis.
En primer lugar, se han comprobado todos los campos disponibles para analizar posibles anomalías o datos incorrectos.
- Se ha comprobado la columna "Invoice ID" para identificar posibles duplicados o valores nulos.
- Se ha eliminado la columna "Branch" ya que no aporta información adicional respecto a la columna "City". Cada sede se relaciona con una ciudad de manera univoca.
- Se han modificado las columnas "unit price",  "tax 5%" y "Total" a formato moneda ($)
- Se han creado las columnas "Mes" y "Mes_Texto" en base a la columna "Date" para identificar el mes en el que se ha realizado la compra.

A continuación, se han generado las tablas dinámicas y graficos deseados en la pestaña "análisis datos".

Finalmente se ha generado el dashboard con los siguientes graficos y datos:
- Se han generado los Big numbers en el dashboard referentes a total de facturas generadas y promedio de productos por cada factura
- Se han generado graficos para analizar el total de ventas por ciudad, y segun el metodo de pago y el genero de los clientes.
- Tambien se han analizado los productos con mas ventas, el total de ventas por ciudad y mes y el grado de satisfaccion asociado a los diferentes productos
- Finalmente se han generado filtros para poder analizar segun mes, ciudad y tipo de cliente.

5. Conclusiones del análisis.
Tras analizar los datos se puede concluir que no hay diferencias significativas en las ventas de las diferentes ciudades, y que el perfil de compras es similar con todos los clientes.
Si se percibe una ligera reduccion de las ventas en el mes de Febrero, quizas debido a alguna promocion especial en los otros meses o a una tendencia general de reduccion del consumo en ese mes que habria que analizar mas en detalle.
Los productos con mejor valoración y que mas compras generaron fueron Fashion accessories y Food and beverages. Todas las valoraciones estan por encima de un 60%, pero habría que obtener mas información para saber como mejorar aun mas esta satisfacción del cliente

Autor:
Lara Rodriguez - https://github.com/lararogu