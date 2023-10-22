<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 


<!-- Su documentación aquí -->
# Actividad: Propiedades CSS, SeudoClases, SeudoElementos y Reglas @css
Crear un documento HTML y probar cada uno de los ejemplos de la sesión 11

### Respuesta

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sesion11</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Actividad Sesion 11</h1>
    <div>
        <p>Tamaño y posición: ejemplo 1</p>
        <p><a href="https://doc-ip.vercel.app/docs/contenido/sesion11">Enlace</a></p>

    </div>
    
    <div>
        <button>Tamaño y posición: ejemplo 2, se probaron todos los ejemplos de la sesion 11 y se modificaron y probaron</button>
    </div>
    <div>
        <ul>
            <li>ELEMENTO1</li>
            <li>ELEMENTO2</li>
            <li>ELEMENTO3</li>
        </ul>
    </div>
    
</body>
</html>
~~~

~~~css
body {
    width: 93.5%;
    height: 100vh;
    margin: 10px;
    padding: 10px;
    color: blueviolet;
    background-color: coral;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 16px;
    border: 30px solid black;
}

h1 {
    width: 30%;
    height: 100px;
    margin: 30px auto;
    padding: 10px;
    color: #fff;
    background-color: rgb(248, 87, 28);
    text-align: center;
    border-radius: 15px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-size: 24px;
    font-weight: bold;
    border-width: 3px;
    border-style: dashed;
    border-color: red;
}

p {
    float: left;
    text-align: center;
    width: 80%;
    height: 100px;
    margin: 10px;
    padding: 20px;
    background-image: url(data:image/jpeg;base64,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);
    background-repeat: no-repeat;
    background-position: center;
    left: 100px;
    font-style: italic;
    font-variant: small-caps;
    border-radius: 10px;
}

button {
    float: none;

    text-align: center;
    width: 80%;
    height: 80px;
    margin: 100px;
    padding: 20px;
}
a {
    color: blue;
  }
  
  a:link {
    background-color: red;
  }
  
  a:active {
    background-color: green;
  }
  p {
    background-color: white;
  }
  
  p:hover {
    background-color: gray;
  }
  button {
    cursor: pointer;
    background-color: blue;
  }
  
  button:active {
    background-color: red;
  }
  button {
    cursor: pointer;
    background-color: blue;
  }
  
  button:disabled {
    cursor: not-allowed;
    background-color: gray;
  }
  ul {
    list-style-type: none;
    background-color: white;
  }
  
  li:nth-of-type(1):hover {
    background-color: red;
  }
  
  li:nth-of-type(2):hover {
    background-color: green;
  }
  
  li:nth-of-type(3):hover {
    background-color: blue;
  }

p {
    font-size: 16px;
    line-height: 2;
  }
  
  p::after {
    content: "→";
    font-size: 20px;
    position: absolute;

  }

  h1::before {
    content: url("https://icons.iconarchive.com/icons/gartoon-team/gartoon-action/48/dialog-apply-icon.png");
}
~~~







