<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->
# Actividad: Propiedades de posicionamiento de CSS
## Objetivo:

__Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.__

Instrucciones:

* Crea un nuevo archivo HTML y CSS.
* En el archivo HTML, crea una estructura básica de página web con dos elementos div.
* En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.

## Solución

>page github
[Link Sesion 10](https://cokain3.github.io/sesion11/) 

~~~html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento de CSS</title>
  <style>
    .elemento-1 {
      position: absolute;
      width: 250px;
      height: 250px;
      top: 100px;
      left: 100px;
      background-color: red;
    }

    .elemento-2 {
      position: relative;
      width: 250px;
      height: 250px;
      top: 130px;
      left: 130px;
      background-color: green;
    }
    div{
        text-align: center; 
    }
  </style>
</head>
<body>
  <div class="elemento-1">elemento 1</div>
  <div class="elemento-2">elemento 2</div>
</body>
</html>
~~~

### Preguntas:

1. ¿Cuál es la diferencia entre los valores position: absolute y position: relative?
2. ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?
3. ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?


### Respuestas:

1. En position: relative , el elemento está posicionado Relativo a sí mismo. Sin embargo, un elemento absolutamente posicionado es relativo a su padre. Un elemento con position: absolute se elimina del flujo normal de documentos. Se posiciona automáticamente en el punto de inicio (top-left esquina) de su elemento padre.

2. Al darle un valor numérico mayor, el elemento se superpondrá sobre los elementos con valores z-index más bajos, controlando así el orden de apilamiento.

3. Especifica si un elemento es tratado como block or inline element y el diseño usado por sus hijos, como flow layout(Diseño de Flujo), grid(Cuadricula) o flex(Flexible). Formalmente la propiedad display establece los tipos de visualización interna y externa de un elemento.





