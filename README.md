# Explicación del esqueleto HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>html skeleton</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <script src="script.js"></script>
</body>
</html>
```

<br>

El DOCTYPE debe estar presente. Informa al navegador que se trata de un documento HTML.

```html
    <!DOCTYPE html>
```

<br>

Una etiqueta de inicio html y una etiqueta de fin html definen el inicio y el final de un documento HTML. Tambien se indica que el idioma del documento es el inglés.

```html
    <html lang="en">

    </html>
```

<br>

El elemento head es un contenedor de metadatos. Los metadatos suelen definir el título del documento, el juego de caracteres, los estilos, los scripts y otra metainformación.

```html
    <head>

    </head>
```

<br>

Para mostrar una página HTML correctamente, un navegador web debe conocer el juego o conjunto (set) de caracteres (char) utilizados en la página. Esto se especifica en la etiqueta < meta > la cual define el charset ("UTF-8").

```html
<meta charset="UTF-8">
```

<br>

El viewport es la área visible de una página web para el usuario.
La parte width = device-width: Establece el ancho de la página que debe seguir la pantalla del dispositivo (que variará según el dispositivo). 
La parte initial-scale = 1.0: Establece el nivel de zoom inicial cuando el navegador carga la página por primera vez.

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

<br>

