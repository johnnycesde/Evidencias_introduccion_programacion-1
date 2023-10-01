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
1. ¿Qué es la propiedad margin?
2. ¿Qué es la propiedad padding?
3. ¿Qué es la propiedad border?
4. ¿Qué es la propiedad border-radius?
5. ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

Respuestas:

1. establece el margen para los cuatro lados. Es una abreviación para evitar tener que establecer cada lado por separado con las otras propiedades de margen: margin-top (en-US), margin-right , margin-bottom y margin-left (en-US). También se permiten valores negativos.
2. es la cantidad de espacio entre el borde y el contenido del elemento. Se dan entre uno y cuatro valores, donde cada valor puede ser una longitud o un porcentaje. Los valores en porcentaje se refieren al ancho del elemento padre.
3. es una de las "propiedades shorthand" que define CSS y que se utilizan para establecer de forma abreviada el valor de una o más propiedades individuales. En este caso, se trata de una de las propiedades shorthand más completas, ya que permite establecer hasta 12 propiedades de forma simultánea.
4. establece el redondeo de la esquina superior izquierda del elemento. El redondeo puede ser un círculo o una elipse, o si uno de los valores es 0 , no se redondeará la esquina, dejándola cuadrada.
5. Algunas unidades de medidas
    * in, pulgadas ("inches", en inglés). Una pulgada equivale a 2.54 centímetros.
    * cm, centímetros.
    * mm, milímetros.
    * pt, puntos. Un punto equivale a 1 pulgada/72, es decir, unos 0.35 milímetros.
    * pc, picas. Una pica equivale a 12 puntos, es decir, unos 4.23 milímetros.