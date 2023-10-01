<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->

# Actividad: Crear una tabla HTML con información sobre productos.

## Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

> page github 
[Link Sesion 4](https://cokain3.github.io/sesion4/) 


# CODIGO

~~~html

<!DOCTYPE html>
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>

    <body>
        <table border="2" cellpading="5" cellspacing="5">

            <thead>
                <tr>
                    <th>Codigo</th>
                    <th>Nombre</th>
                    <th colspan="7">Descripcion</th>
                    <th>Stock</th>
                    <th>Precio</th>
                    <th colspan="5">Fecha de creacion</th>

                </tr>

            </thead>
            <tbody>
                <tr>
                    <td rowspan="2"> 001</td>
                    <td rowspan="2">Iphone 14 Pro Max</td>
                    <td colspan="7">
                        <p>El Iphone 14 Pro Max Es el smartphone mas potente del mercado cuenta con una
                            pantalla Oled de 6.7 pulgadas un procesador A 16 Bionic y un sistema de camaras de 48
                            megapixeles </p>
                    </td>
                    <td> 10</td>
                    <td> 4,899,000 COP </td>
                    <td colspan="5"> 2022.09.21 </td>
                <tr>
                    <td colspan="7">
                        <p>El Iphone 14 Pro Max esta disponible en cuatro colores. Grafito plata oro y tierra </p>
                    </td>
                    <td colspan="7">100</td>
                </tr>
                <tr>
                    <td rowspan="2"> 002</td>
                    <td rowspan="2">MacBook Pro M2 Pro</td>
                    <td colspan="7">
                        <p>MacBook Pro M2 Pro Es el nuevo portatil profesional de Apple. cuenta con el procesador M2 Pro
                            una pantalla liquid Retina XDR y un sistema de camaras true Depth,con Camaras time HD</p>


                    </td>
                    <td> 10 </td>
                    <td> 10,499,000 COP </td>
                    <td colspan="5"> 2022.06.06 </td>
                <tr>
                    <td colspan="7">
                        <p>El MacBook Pro M2 Pro esta disponible en dos colores. Gris espacial y plata </p>
                    </td>
                    <td colspan="7">75</td>
                </tr>
                <tr>
                    <td rowspan="2"> 010</td>
                    <td rowspan="2">Nintendo switch OLED </td>
                    <td colspan="7">
                        <p> La nintendo switch OLED es la version mejorada de la consola Nintendo OLED. cuenta con una
                            pantalla de 7 pulgadas mas almacenamiento y un soporte ajustable.</p>
                    </td>
                    <td> 10</td>
                    <td> 1,099,000 COP </td>
                    <td colspan="5"> 2021.10.08 </td>
                <tr>
                    <td colspan="7">
                        <p>La nintendo switch OLED esta disponible en dos colores. Blanco y negro</p>
                    </td>
                    <td colspan="7">75</td>
                </tr>
                <tr>
                    <td rowspan="2"> 05</td>
                    <td rowspan="2">Samsumg Galaxy s23</td>
                    <td colspan="7">
                        <p> Resolucion de camara frontal 12MP resolucion de camara posterior 200MP+ 10MP +12MP y
                            capacidad de la bateria 50000mAh.</p>
                    </td>
                    <td> 500</td>
                    <td> 997,000 COP </td>
                    <td colspan="5"> 2021.10.08 </td>
                <tr>
                    <td colspan="7">
                        <p>Samsumg Galaxy s23 esta disponible en tres colores. Blanco y negro y rojo</p>
                    </td>
                    <td colspan="7">85</td>
                </tr>
                <tr>
                    <td rowspan="2"> 06</td>
                    <td rowspan="2">Samsumg Galaxy S23+6.6</td>
                    <td colspan="7">
                        <p> RAM 8 gb y 256 Resolucion de camara frontal 15MP resolucion de camara posterior 300MP+ 12MP
                            +12MP y
                            capacidad de la bateria 40000mAh.</p>
                    </td>
                    <td> 300</td>
                    <td> 1,593,000 COP </td>
                    <td colspan="5"> 2022.12.18 </td>
                <tr>
                    <td colspan="7">
                        <p>Samsumg Galaxy S23+6.6 esta disponible en cuatro colores. Blanco, negro ,rojo y azul</p>
                    </td>
                    <td colspan="7">110</td>
                </tr>
                <tr>
                    <td rowspan="2"> 07</td>
                    <td rowspan="2"> Xiaomi Redmi 12S</td>
                    <td colspan="7">
                        <p> RAM 8 gb y 256 pantalla 6.79 pulgadas. Procesador Mediatek Helio G88,Resolucion de camara
                            frontal 15MP resolucion de camara posterior 300MP+ 10MP +15MP y
                            capacidad de la bateria 35000mAh.</p>
                    </td>
                    <td> 300</td>
                    <td> 2,123,000 COP </td>
                    <td colspan="5"> 2022.10.09 </td>
                <tr>
                    <td colspan="7">
                        <p>Xiaomi Redmi 12S esta disponible en cuatro colores. verde,amarillo ,rojo y azul</p>
                    </td>
                    <td colspan="7">50</td>
                </tr>
                <tr>
                    <td rowspan="2"> 08</td>
                    <td rowspan="2"> Nokia Ultra Plus R258</td>
                    <td colspan="7">
                        <p> RAM 9 gb y 128 pantalla 7.45 pulgadas. Procesador Packed Helio R88,Resolucion de camara
                            frontal 20MP resolucion de camara posterior Quad Android 300MP+ 15MP +12MP y
                            capacidad de la bateria 5000mAh.</p>
                    </td>
                    <td> 100</td>
                    <td> 3,000,000 COP </td>
                    <td colspan="5"> 2022.01.09 </td>
                <tr>
                    <td colspan="7">
                        <p>Nokia Ultra Plus R258 esta disponible en tres colores. verde,rojo y azul</p>
                    </td>
                    <td colspan="7">300</td>
                </tr>
                <tr>
                    <td rowspan="2"> 09</td>
                    <td rowspan="2"> One Plus 11</td>
                    <td colspan="7">
                        <p> Pantalla Amoled 6.7 pulgadas con un brillo maximo de 1.3000 nits buenos colores y angulos,
                            Procesador snapdragon 8 gen 2 camara de 50 MPX capacidad de la bateria 5000mAh.</p>
                    </td>
                    <td> 400</td>
                    <td> 5,000,000 COP </td>
                    <td colspan="5"> 2023.04.12 </td>
                <tr>
                    <td colspan="7">
                        <p>One Plus 11 esta disponible en tres colores. plateado,rojo intenso y azul perlado</p>
                    </td>
                    <td colspan="7">200</td>
                </tr>
                <tr>
                    <td rowspan="2"> 10</td>
                    <td rowspan="2"> Google Pixel Pro</td>
                    <td colspan="7">
                        <p> La mejor camara frontal nocturna sony IMX766 de 50 MPX,Pantalla Oled 6.7 pulgadas con un
                            brillo maximo de 1.500 nits buenos colores y angulos,
                            Procesador snapdragon 9,capacidad de la bateria 5000mAh carga rapida</p>
                    </td>
                    <td> 400</td>
                    <td> 5,850,000 COP </td>
                    <td colspan="5"> 2023.05.12 </td>
                <tr>
                    <td colspan="7">
                        <p>Google Pixel Pro disponible en cinco colores. verde oscuro,negro,rojo y azuly blanco</p>
                    </td>
                    <td colspan="7">200</td>
                </tr>
    </body>

</html>

~~~

