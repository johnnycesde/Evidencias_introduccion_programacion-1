<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


<!-- Su documentación aquí -->

# Actividad: Creando mi primer sitio web
## Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

- Index o página de inicio
- Acerca
- Contacto

> page github
[Link Sesion 2](https://cokain3.github.io/sesion2/) 


# index.html

~~~html

<!DOCTYPE html>
<html>

<head>
    <title>Mi primer sitio web</title>
</head>

<body bgcolor="darkgray">
    
    <header>
        <h1 align="center" style="color: aliceblue;">Mi sitio web</h1>
    </header>

    <nav align="center">
        <a href="acerca.html" style="color: aliceblue;">Acerca</a>
        <a href="contacto.html" style="color: aliceblue;">Contacto</a>
    </nav>

    <main align="center" style="color: aliceblue;">
        <p>Bienvenidos a mi sitio sobre XYZ</p>
        <p>Aqui encontraran informacion sobre nuestros servicios y productos</p>
    </main>


    <center><img src="imgindx.webp"></center>

    <footer align="right" style="color: aliceblue;">

        <P style="font-size: smaller;"><i style="color: aliceblue;">Copyright 2023 - Juan perez</i></P>
        <P style="font-size: smaller;"><i>juanperez@email.com</i></P>
    </footer>

</body>

</html>

~~~

# About.html

~~~html

<!DOCTYPE html>
<html>

<head>
    <title>Sobre nosotros</title>
</head>

<body bgcolor="ivory">

    <header>
        <h1 align="center">Sobre nosotros</h1>
    </header>

    <nav align="center">
        <a href="index.html">Inicio</a>
        <a href="contacto.html">Contacto</a>
    </nav>

    <section align="center">
        <h2>Historia</h2>
        <p>Fundada en 2010 ...</p>

        <article align="center">
            <h3>Mision y vision</h3>
            <p>Nuestra mision es...</p>
        </article>

        <center><img src="imgacr.webp"></center>

    </section>

    <footer align="right">
        <P style="font-size: smaller;"><i>Copyright 2023 - Juan perez</i></P>
        <P style="font-size: smaller;"><i>juanperez@email.com</i></P>
    </footer>

</body>

</html>


~~~

# Contact.html

~~~html

<!DOCTYPE html>
<html>

<head>
    <title>Contacto</title>
</head>

<body bgcolor="mistyrose">

    <header>
        <h1>Contacto</h1>
    </header>

    
    <nav>
        <a href="index.html">Inicio</a>
        <a href="acerca.html">Acerca</a>
    </nav>

    <main>

        
        <form>
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre"><br>

            <label for="email">Email:</label>
            <input type="email" id="email"><br>

            <label for="mensaje">Mensaje:</label>
            <input type="mensaje" id="textarea"><br>

            <input type="submit" value="enviar">
        </form>
        
        
        <aside>
            <h3>Ubicación</h3>
            <p>Calle falsa 123</p>
        </aside>

        <p><img align="left" src="imgcont.webp">
        <ul><li>1 ventas</li>
            <li>2 soporte</li>
            <li>3 aliados</li>
        </ul>
        </p>

    </main>

    
    <footer align="right">
        <P style="font-size: smaller;"><i>Copyright 2023 - Juan perez</i></P>
        <P style="font-size: smaller;"><i>juanperez@email.com</i></P>
    </footer>

</body>

</html>

~~~
