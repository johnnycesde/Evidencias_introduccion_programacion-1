<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->

# Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5
## Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 Imagenes
- 2 Videos
- 4 Audios
- 2 Inline Frame

Utiliza encabezados para títulos en cada elemento (\<h1>...\<h6>).

Crea una descripción para cada elemento utilizando párrafos (\<p>).

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

Usa \<strong> para resaltar texto importante.

Utiliza \<br> para insertar saltos de línea si es necesario.

Agrega \<span> para aplicar estilos específicos a porciones de texto.

Emplea \<i> para enfatizar o dar énfasis a palabras o frases.

Utiliza \<u> para subrayar texto cuando sea necesario.

Considera el uso de \<div> para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.





## Solución
> page github 
[Link Sesion 3](https://cokain3.github.io/sesion3/) 

### codigo

~~~html 

<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif, 'Arial Narrow', Arial, sans-serif, sans-serif;
        }

        header {
            background-color: #855121;
            color: white;
            padding: 20px;
            text-align: center;

        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;

        }

        h2 {
            color: rgba(194, 131, 14, 0.671);
        }

        footer {
            background-color: #855121;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>Imágenes</h2>

        <h3>Espresso</h3>
        <p>El café expreso (también denominado café espresso, café exprés, café express o café solo) es una forma de
            preparación de café. Debe su término a la obtención de esta bebida a través de una cafetera expreso. <br>Se
            caracteriza por su rápida preparación a una alta presión y por un sabor y textura más concentrados.
            <a href="https://es.wikipedia.org/wiki/Caf%C3%A9_expreso">Mas información</a>
        </p>
        <img src="expresso.jpg" alt="espresso" width="100">

        <h3>Capuchino</h3>
        <p>El capuchino (del italiano cappuccino a su vez del alemán kapuziner) es una bebida nacida en Austria,
            preparada con café expreso y leche montada con vapor para darle cremosidad.<br> Un capuchino se compone de
            125
            ml de leche y 25 ml de café expreso
            <a href="https://es.wikipedia.org/wiki/Capuchino_(caf%C3%A9)">Mas información</a>
        </p>
        <img src="capuchino.jpg" alt="capuchino" width="100">

        <h3>Maquiato</h3>
        <p>El café manchado o caffè macchiato [kaffɛ (m)makkjato] en italiano, también llamado espresso macchiato, es
            un café cortado típico de Italia, <br> consiste en un expreso con una pequeña cantidad de leche caliente y
            espumada. En España se suele denominar café cortado.
            <a href="https://es.wikipedia.org/wiki/Caff%C3%A8_macchiato">Mas información</a>
        </p>
        <img src="maquiato.jpg" alt="maquiato" width="100">

        <h3>Mocca</h3>
        <p>Un café moca es una variante del café con leche. Como este, suele llevar un tercio de expreso y dos tercios
            de leche vaporizada, pero se añade una parte de chocolate,<br> normalmente en forma de jarabe de chocolate,
            aunque algunas máquinas usan chocolate en polvo instantáneo. Los mochas contienen chocolate negro o con
            leche.
            <a href="https://es.wikipedia.org/wiki/Caf%C3%A9_moca">Mas información</a>
        </p>
        <img src="moca.jpg" alt="mocca" width="100">


    </section>

    <section>
        <h2>Videos</h2>

        <h2>Espresso</h2>
        <p><i>Preparación Espresso</i></p>
        <video src="vidlatte1.mp4" controls></video>

        <h2>Moka</h2>
        <p><i>Preparación en cafetera </i><strong>Moka</strong></p>
        <video src="vid2.mp4" controls></video>

    </section>

    <section>
        <h2>Audios</h2>

        <h4>Loffi chill</h4>
        <p><u>Bodleasson</u></p>
        <audio src="audio.mp3" controls></audio>

        <h4>Ambiental clasicc guitar</h4>
        <p><u>William king</u></p>
        <audio src="audio.mp3" controls></audio>

        <h4>Tuesday</h4>
        <p><u>Amaksi</u></p>
        <audio src="audio.mp3" controls></audio>

        <h4>Coffe chill out</h4>
        <p><u>Roman belov</u></p>
        <audio src="audio.mp3" controls></audio>

    </section>

    <section>
        <h5>iFrames</h5>
        <p><span>Historia del cafe</span></p>
        <iframe src="https://es.wikipedia.org/wiki/Historia_del_caf%C3%A9" width="500" height="300"></iframe>

        <p><span>Art latte</span></p>
        <iframe src="https://en.wikipedia.org/wiki/Latte_art" width="500" height="300"></iframe>

    </section>

    <footer>
        Gustavo Adolfo Vanegas Marin
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>

~~~