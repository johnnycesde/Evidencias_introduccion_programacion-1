<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->


Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

1. Crea un nuevo archivo HTML y CSS.
2. En el archivo HTML, agrega el siguiente código:

~~~html

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>

~~~

3. En el archivo CSS, agrega el siguiente código:

~~~css

.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}

~~~

4. Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles.

5. Practicar el uso de las propiedades de espaciado.

* Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.

~~~css

.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}

~~~

* Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.

~~~css

.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

~~~

* Border: Agrega un borde de 5 píxeles de color rojo.

~~~css

.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

~~~

* Border-radius: Agrega un radio de esquina de 10 píxeles.

~~~css

.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

~~~

* Unidades de medida: Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.

~~~css

.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}

~~~

Preguntas:
¿Qué es la propiedad margin?
¿Qué es la propiedad padding?
¿Qué es la propiedad border?
¿Qué es la propiedad border-radius?
¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?