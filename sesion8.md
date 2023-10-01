<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->

# Actividad: Aplicando estilos con selectores CSS
## El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado \<header>
- Tres párrafos \<p>
- Una imagen \<img>
- Un pie de página \<footer>

__Aplica los siguientes estilos usando selectores de etiqueta:__

Color rojo a los encabezados \<h1>

Color azul a los párrafos \<p>

Borde grueso negro a la imagen \<img>

__Aplica los siguientes estilos usando seleccionadores de clase:__

Color verde a los elementos con la clase ".destacado"

Tamaño de fuente grande a los elementos con la clase ".grande"

__Aplica los siguientes estilos usando seleccionadores de ID:__

Color amarillo al elemento con ID "#principal"

Sombra al elemento con ID "#sombras"

__Aplica los siguientes estilos usando seleccionadores descendientes:__

Color gris a los párrafos dentro de un \<div>

Centrar el contenido de la sección \<section>

## Solución
>page github
[Link Sesion 8](https://cokain3.github.io/sesion8/) 

### INDEX.html

~~~html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Actividad8</title>
    <link rel="stylesheet" href="stylo.css">
</head>

<body>

    <header>
        <h1>VIDEOJUEGOS CLÁSICOS</h1>
    </header>
    <section>
        <h3 class="destacado">Donkey Kong</h3>
        <p>Donkey Kong es el primer juego creado por Shigeru Miyamoto y supuso la creación de dos de los personajes más
            importantes de Nintendo: Mario y Donkey Kong.</p><br>
        <h3 class="destacado">Pac-Man</h3>
        <p>El popular comecocos llegó a las máquinas de arcade en 1980 y es uno de los juegos clásicos más importantes
            de la
            historia. Un sencillo juego en el que tan solo hay que ir recogiendo puntos y otros objetos hasta limpiar el
            nivel y
            pasar al siguiente.</p><br>
        <h3 class="destacado">Super Mario Bros</h3>
        <p>Super Mario Bros es el primer juego con Mario de protagonista. Desarrollado por Miyamoto y publicado por
            Nintendo
            para NES en 1985, se trata de un juego de plataformas que ha trascendido al medio y se ha convertido en todo
            un
            icono de la cultura popular.</p><br>
    </section>
    <div>
        <p>Los recuerdas? Una década dorada que dio origen a multitud de clásicos</p>
        <img src="img/Nintendo-Movil.jpg" alt="Imagen juegos clasicos">
    </div>
    <footer>
        <p class="grande">Gustavo Adolfo Vanegas Marin</p>
        <p id="principal">Juegos clásicos de los 80s</p>
        <p id="sombras">Copyright © 2023, My Website. Todos los derechos reservados.</p>
    </footer>

</body>

</html>

~~~

### STYLO.CSS

~~~css

/*selectores de etiqueta*/
h1 {
    color: red;
}

p {
    color: blue;
}

img {
    border: 10px solid black;
}

/*seleccionadores de clase*/

.destacado {
    color: green;
}

.grande {
    font-size: large;
}

/*seleccionadores de ID*/

#principal {
    color: yellow;
}

#sombras {
    color: yellow;
    font-weight: 900;
    text-shadow: 3px 3px 0px green, 5px 5px 0px black;
}

/*seleccionadores descendientes*/
div p {
    color: gray;
    text-align: center;
}
section h3, p {
    text-align: center;
}

~~~