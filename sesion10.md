<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->

# **Propiedades de posicionamiento de CSS**

![imag1ses10](image-112.png)

La propiedad position de CSS determina cómo se posiciona un elemento en un documento. Hay cinco valores diferentes para la propiedad position:

- static: El elemento se posiciona de acuerdo con el flujo normal del documento.

- absolute: El elemento se posiciona de forma absoluta, es decir, se coloca en una posición específica en la página, independientemente del flujo normal del documento.

- relative: El elemento se posiciona de forma relativa, es decir, se desplaza desde su posición original en el flujo normal del documento.

- fixed: El elemento se posiciona de forma fija, es decir, se coloca en una posición específica en la ventana del navegador y permanece en esa posición incluso cuando el usuario se desplaza por la página.
Propiedades de visualización de CSS


# **Propiedades de visualización de CSS**

![imag2ses10](image-113.png)

La propiedad display de CSS determina cómo se muestra un elemento en una página web. Hay cuatro valores diferentes para la propiedad display:

- block: El elemento se muestra como una caja de bloque, que ocupa toda la anchura de su contenedor y se muestra en una nueva línea.

- inline: El elemento se muestra como una caja de línea, que se muestra en la misma línea que el texto circundante.

- inline-block: El elemento se muestra como una caja de línea, pero puede tener una anchura y una altura definidas.

- none: El elemento no se muestra en la página web.


# **Ejemplos de uso de las propiedades de posicionamiento y visualización de CSS**

- Elemento posicionado de forma absoluta:

![imag3ses10](image-114.png)

Este código posicionará el elemento .absoluto a 10 píxeles de la parte superior y izquierda de la ventana del navegador.

- Elemento posicionado de forma relativa:

![imag4ses10](image-115.png)

Este código posicionará el elemento .relativo a 10 píxeles de su posición original en el flujo normal del documento.

- Elemento posicionado de forma fija:

![imag5ses10](image-116.png)

Este código posicionará el elemento .fijo a 10 píxeles de la parte superior y izquierda de la ventana del navegador y permanecerá en esa posición incluso cuando el usuario se desplaza por la página.

- Elemento posicionado de forma sticky:

![imag6ses10](image-117.png)

Este código posicionará el elemento .sticky a 10 píxeles de la parte superior de la ventana del navegador cuando el usuario se desplaza por la página, pero se volverá a comportar de forma normal cuando el usuario alcance el borde superior de la ventana del navegador.

# **Ejemplo de HTML donde se usan todas las clases CSS anteriores**

```
html

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento y visualización de CSS</title>
  <style>
    .bloque {
      display: block;
      width: 200px;
      height: 100px;
      background-color: red;
    }

    .en línea {
      display: inline;
      width: 100px;
      height: 50px;
      background-color: green;
    }

    .inline-bloque {
      display: inline-block;
      width: 100px;
      height: 50px;
      background-color: blue;
    }

    .absoluto {
      position: absolute;
      top: 100px;
      left: 100px;
      background-color: yellow;
    }

    .relativo {
      position: relative;
      top: 100px;
      left: 100px;
      background-color: orange;
    }

    .fijo {
      position: fixed;
      top: 100px;
      left: 100px;
      background-color: pink;
    }

    .sticky {
      position: sticky;
      top: 100px;
      left: 100px;
      background-color: purple;
    }
  </style>
</head>
<body>
  <h1>Ejemplo de posicionamiento y visualización de CSS</h1>

  <div class="bloque">
    Este es un elemento de bloque.
  </div>

  <span class="en línea">
    Este es un elemento de línea.
  </span>

  <div class="inline-bloque">
    Este es un elemento de línea con ancho y altura definidos.
  </div>

  <div class="absoluto">
    Este elemento está posicionado de forma absoluta.
  </div>

  <div class="relativo">
    Este elemento está posicionado de forma relativa.
  </div>

  <div class="fijo">
    Este elemento está posicionado de forma fija.
  </div>

  <div class="sticky">
    Este elemento está posicionado de forma sticky.
  </div>
</body>
</html>

```
