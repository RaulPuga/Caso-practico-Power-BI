# Caso-practico-Power-BI

# Caso práctico en Power Bi del diplomado Analítica y Ciencia de datos

# Introducción:
### Continuando con la empresa SRL, ahora nos encontramos con los datos del departamento de ventas que incluyen información detallada sobre las operaciones realizadas del año 2020 al 2023, estos datos son cruciales para el análisis y la toma de decisiones en el departamento de Ventas.
### El trabajo se dividirá de la siguiente forma:

Objetivo general

Variables a utilizar

Análisis en Power BI

Conclusión

Referencias

# Objetivo General:
### Crear un dashboard de ventas en Power BI Desktop con el fin de facilitar la toma de decisiones del departamento. 

# Variable de la base de datos:
- Row ID: Id de la operación
- Order ID: Id de la orden
- Order Date: Día de realización de la orden
- Ship Date: Día de entrega de la orden
- Ship Mode: Forma de envío
- Customer ID: Id del cliente
- Customer Name: Nombre del cliente
- Segment: Segmento del producto
- Country/Region: País de ubiación del clientes
- City: Ciudad de ubicación del cliente
- State/Province: Estado de ubiación del cliente
- Postal Code: Código de postal
- Region: Región
- Product ID: Id del producto
- Category: Categoría del producto
- Sub-Category: Sub categoría del producto
- Product Name: Nombre del producto
- Sales: Ventas en dolares
- Quantity: Número de unidades
- Discount: Descuento
- Profit: Utilidad
### Se crearon las siguientes variables:
- Precio unitario = Sales / Quatity
- Costo total=  sales - Profit



# Análisis en Power BI
### En la primera hoja podemos ver un tablero completo donde en la parte inferior aparece información clave como: Precio promedio, utilidad, costo promedio y días promedio de envío, en la lateral izquierda se presentan gráficas de proporciones en porcentaje de los años 2020 a 2023 con información de unidades vendidas, ventas en dolares y utilidad, en la parte lateral derecha se encuentran todos los filtros que se pueden aplicar como son: país, forma de envío, categoría del producto y años, en la parte central la primera gráfica muestra la utilidad por sub categoría, el cuadro siguiente muestra el top 3 de los clientes que más compraron y la última gráfica muestra los meses con más pedidos.


<img width="1002" alt="Captura de Pantalla 2024-08-16 a la(s) 9 00 34" src="https://github.com/user-attachments/assets/2c76e809-f8a4-4098-aee8-01334cd6d885">

### En la segunda hoja podemos ver un mapa con las ventas por estado, entre más grande sea el círuclo mayor ventas registro en el período.
<img width="1004" alt="Captura de Pantalla 2024-08-16 a la(s) 8 55 05" src="https://github.com/user-attachments/assets/43bdfe6b-86b3-472f-b79d-b4f8068ddc63">

### En la última hoja podemos apreciar un gráfico de las ventas por ciudad y estado, entre más grande sea el rectángulo, mayores ventas se registraron en esa ciudad en el período análizado.
<img width="994" alt="Captura de Pantalla 2024-08-16 a la(s) 8 55 18" src="https://github.com/user-attachments/assets/165d1fa0-2ba4-48f2-be7f-f47592fe3d2d">

### El dashboard en general permiten navegar entre las pestañas dando click en el apartado de navegar entre páginas además permiten ver mas detalles dando clic derecho y seleccionar la opción que dice optener detalles.


# Conclusión
Depués de analizar los datos podemos decir que:

El precio promedio es de $60, el costo promedio toal de $199 la utilidad de 292,000 y se tarda la empresa en promedio 4 días en entregar los prodcutos a sus clientes. 

Los meses que más unidades se vendierom fueron Septiembre, noviembre y diciembre por lo que podemos decir que es un producto con una estacionalidad marcada en el mercado. 

El año con mayores unidades vendidas fue: 2023, esto se vio reflejado en la venta total y en la utilidad ya que fue el mismo año el más alto, si analizamos estos datos, podemos observar una tendencia a la alta, lo cual es muy bueno para la empresa ya que se indica que se encuentran en una face de expanción.

Las categorías de artículos más vendidos fueron las fotocopiadoras y los celulares.

Los estados con mayores ventas fueron California y New York.

Las ciudades con mayores ventas fueron los Ángeles y San Fancisco, ambas del estado de California, el cual presenta el mayor número de ventas comon ya se comento en el punto pasado.

# Referencias:
- Datdata. (2022, 26 enero). Curso completo de Power BI (2023) [Vídeo]. YouTube. https://www.youtube.com/watch?v=sjrlIAQnD8M
-  Microsoft. (2022). Connectors in Power Query. Microsoft Lean. Recuperado el Octubre 26, 2022 de
  https://learn.microsoft.com/en-us/power-query/connectors/
- Microsoft. (2022). Power BI get started documentation - Power BI. Microsoft Learn. Recuperado el
  Octubre 26, 2022, de https://learn.microsoft.com/en-us/power-bi/fundamentals/
- Microsoft. (2022, Julio 15). Get samples for Power BI - Power BI. Microsoft Learn. Recuperado el
Octubre 24, 2022, de
https://learn.microsoft.com/en-us/power-bi/create-reports/sample-datasets#download-original-sam
ple-power-bi-files
- Microsoft. (2022, Agosto 31). What is Power Query? - Power Query. Microsoft Learn. Recuperado el
Octubre 10, 2022, de
https://learn.microsoft.com/en-us/power-query/power-query-what-is-power-query
- Microsoft (2023, Octubre 20). Dax Overview. Recuperado el Junio 23, 2023 de
https://learn.microsoft.com/en-us/dax/dax-overview


