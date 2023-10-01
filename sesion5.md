<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->


# Actividad: Diseñar un formulario de pedido de un producto
__Objetivo:__

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

__*Instrucciones:*__

- Crear un nuevo documento HTML.
- Crear un formulario con los siguientes campos:
- Nombre del producto
- Cantidad
- Precio unitario
- Precio total
- Dirección de envío
- Información de contacto (nombre, correo electrónico, número de teléfono)
- Agregar los siguientes campos relacionados al formulario:
- Método de pago
- Fecha de entrega
- Comentarios
- Utilizar las etiquetas HTML apropiados para cada campo.

>page github
[Link Sesion 5](https://cokain3.github.io/sesion5/) 

# Index.html

~~~html

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Pedido</title>
    <link rel="stylesheet" href="stylo.css">
    </head>
<body>
   <div class="tituform">
    <h1>Formulario de Pedido</h1>
   </div> 
    <form action="procesar_pedido.php" method="POST">
        <label for="nombre_producto">Nombre del producto:</label>
        <input type="text" id="nombre_producto" name="nombre_producto" required><br><br>

        <label for="cantidad">Cantidad:</label>
        <input type="number" id="cantidad" name="cantidad" required><br><br>

        <label for="precio_unitario">Precio unitario:</label>
        <input type="number" step="0.01" id="precio_unitario" name="precio_unitario" required><br><br>

        <label for="precio_total">Precio total:</label>
        <input type="number" step="0.01" id="precio_total" name="precio_total" required><br><br>

        <label for="direccion_envio">Dirección de envío:</label>
        <textarea id="direccion_envio" name="direccion_envio" rows="4" cols="50" required></textarea><br><br>

        <label for="nombre_contacto">Información de contacto (nombre):</label>
        <input type="text" id="nombre_contacto" name="nombre_contacto" required><br><br>

        <label for="correo_contacto">Información de contacto (correo electrónico):</label>
        <input type="email" id="correo_contacto" name="correo_contacto" required><br><br>

        <label for="telefono_contacto">Información de contacto (número de teléfono):</label>
        <input type="tel" id="telefono_contacto" name="telefono_contacto" required><br><br>

        <label for="metodo_pago">Método de pago:</label>
        <select id="metodo_pago" name="metodo_pago" required>
            <option value="tarjeta_credito">Tarjeta de Crédito</option>
            <option value="tarjeta_debito">Tarjeta de Débito</option>
            <option value="paypal">PayPal</option>
            <option value="transferencia">Transferencia Bancaria</option>
        </select><br><br>

        <label for="fecha_entrega">Fecha de entrega:</label>
        <input type="date" id="fecha_entrega" name="fecha_entrega" required><br><br>

        <label for="comentarios">Comentarios:</label>
        <textarea id="comentarios" name="comentarios" rows="4" cols="50"></textarea><br><br>

        <input type="submit" value="Enviar Pedido">
    </form>
</body>
</html>

~~~

# STYLO.CSS

~~~css

/* Estilos generales
*/
.tituform {
    background-color: #f0e8e8;
    padding: 0px;
    border: 1px solid #ccc;
    border-radius: 5px;
    text-align: center;
    font-size: 18px;
    color: #000000;
}

body {
    font-family: Arial, sans-serif;
    margin: 20;
    background: -moz-linear-gradient(top, #0FF3E8 0%, #139CA4 84%, #C59237 100%);
    background: -webkit-linear-gradient(top, #0FF3E8 0%, #139CA4 84%, #C59237 100%);
    background: linear-gradient(to bottom, #0FF3E8 0%, #139CA4 84%, #C59237 100%);
    background-attachment: fixed;
    color: #fff;
    display: grid;
    justify-content: center;
    align-items: center;
    height: auto;
}

.container {

    background-color: rgba(255, 255, 255, 0.9);
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    border-radius: 5px;
    padding: 30px;
    width: 80%;
    max-width: 600px;
    text-align: center;

}

h1 {
    font-size: 24px;
    margin-bottom: 20px;
}

/* Estilos para el formulario */
form {
    margin-top: 20px;
}

label {
    font-weight: bold;
    display: block;
    margin-bottom: 5px;
}

input[type="text"],
input[type="number"],
input[type="email"],
input[type="tel"],
textarea,
select {
    width: 90%;
    padding: 5px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

input[type="submit"] {
    background-color: #0056b3;
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    width: 100%;
}

input[type="submit"]:hover {
    background-color: #003f80;
}

~~~
