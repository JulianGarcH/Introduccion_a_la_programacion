<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->


# **Propiedades de espaciado y unidades de medidad css y ejemplos**


## **Propiedades de espaciado**

![ima1ses9](image-85.png)

**Margin (Margen):**

- Propiedades: margin-top, margin-right, margin-bottom, margin-left o la propiedad abreviada margin.

Ejemplo con unidades de medida:

![imag2ses9](image-86.png)

**Padding (Relleno):**

- Propiedades: padding-top, padding-right, padding-bottom, padding-left o la propiedad abreviada padding.

Ejemplo con unidades de medida:

![ima3ses9](image-87.png)

**Border (Borde):**

Propiedades: border-width, border-style, border-color, border-top, border-right, border-bottom, border-left, etc.

Ejemplo:

![imag4ses9](image-88.png)

**Espaciado entre letras (letter-spacing):**

Propiedad: letter-spacing.

Ejemplo:

![ima5ses9](image-89.png)

**Espaciado entre palabras (word-spacing):**

Propiedad: word-spacing.

Ejemplo:

![ima6ses9](image-90.png)


# **Unidades de medida más comunes en CSS**

![ima7ses9](image-91.png)


En el contexto de CSS (Cascading Style Sheets), las unidades de medida se utilizan para definir dimensiones y tamaños de elementos en una página web. CSS admite diversas unidades de medida que permiten especificar longitudes, anchuras, alturas, márgenes, rellenos y otros atributos dimensionales. Algunas de las unidades de medida más comunes en CSS incluyen:

**Píxeles (px): Representa los píxeles en la pantalla. 1px = 1 píxel de la pantalla. Es la unidad de medida más común y precisa.**

Ejemplo:

![imag8ses9](image-92.png)

**Porcentaje (%): Se refiere al porcentaje del tamaño del elemento padre. Por ejemplo, el 50% de la altura del elemento padre.**

Ejemplo:

![imag9ses9](image-93.png)

**Em: Basado en el tamaño de fuente del elemento. 1em = tamaño de fuente actual. Cambia si el tamaño de fuente cambia.**

Ejemplo:

![imag10ses9](image-94.png)

**Rem: Igual que em pero basado en el tamaño de fuente de la raíz <html> en lugar del elemento.**

Ejemplo:

![imag11ses9](image-95.png)

**Vw (view width): Ancho de la ventana viewport.**

Ejemplo:

![ima12ses9](image-96.png)

**Vh (view height): Altura de la ventana viewport.**

Ejemplo:

![ima13ses9](image-97.png)

**Cm (centímetros): Representa el tamaño en centímetros. 1cm = 1/100 de metro.**

Ejemplo:

![ima14ses9](image-98.png)

**Mm (milímetros): Representa el tamaño en milímetros. 1mm = 1/1000 de metro.**

Ejemplo:

![ima15ses9](image-99.png)

**In (pulgadas): Representa el tamaño en pulgadas. 1in = 2.54cm.**

Ejemplo:

![ima16ses9](image-100.png)

**Pt (puntos): Unidad tipográfica tradicional. 1pt = 1/72 de pulgada.**

Ejemplo:

![imag17ses9](image-101.png)

**Pc (picas): Otra unidad tipográfica. 1pc = 12pt.**

Ejemplo:

![ima18ses9](image-102.png)


# **Actividad: Propiedades de espaciado y unidades de medida**

Objetivo:

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

1. Crea un nuevo archivo HTML y CSS.

1. En el archivo HTML, agrega el siguiente código:

![imag19ses9](image-103.png)

1. En el archivo CSS, agrega el siguiente código:

![ima20ses9](image-104.png)

1. Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles.

1. Practicar el uso de las propiedades de espaciado.

- Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.

![imag21ses9](image-105.png)

- Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.

![imag22ses9](image-106.png)

- Border: Agrega un borde de 5 píxeles de color rojo.

![ima23ses9](image-107.png)

- Border-radius: Agrega un radio de esquina de 10 píxeles.

![imag24ses9](image-108.png)

- **Unidades de medida:** Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.

![imag25ses9](image-109.png)


# **Preguntas:**

1. ¿Qué es la propiedad margin?

1. ¿Qué es la propiedad padding?

1. ¿Qué es la propiedad border?

1. ¿Qué es la propiedad border-radius?

1. ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

## **Solucion**

![imagsolses9](image-110.png)
![imaso9-2se9](image-111.png)

1. **¿Qué es la propiedad margin?:**

La propiedad CSS margin establece el margen para los cuatro lados. Es una abreviación para evitar tener que establecer cada lado por separado con las otras propiedades de margen: margin-top (en-US), margin-right , margin-bottom y margin-left (en-US).

1. **¿Qué es la propiedad padding?**

La propiedad padding es la que crea el espacio o área alrededor del contenido de un elemento. Consiste en el relleno superior, derecho, inferior e izquierdo. En CSS se escriben como padding-top:, padding-right:, padding-bottom: y padding-left:.

1. **¿Qué es la propiedad border?**

La propiedad border permite definir en una única regla todos los bordes de los elementos seleccionados. Se puede utilizar border para definir el o los valores siguientes: border-width , border-style , border-color .

1. **¿Qué es la propiedad border-radius?**

La propiedad CSS border-top-left-radius establece el redondeo de la esquina superior izquierda del elemento. El redondeo puede ser un círculo o una elipse, o si uno de los valores es 0 , no se redondeará la esquina, dejándola cuadrada.

1. **¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?**

- **Píxeles (px):** Las unidades de píxeles son absolutas y proporcionan un control preciso sobre el espaciado. Por ejemplo, margin: 10px; establecerá un margen de 10 píxeles.

- **Porcentaje (%):** Las unidades de porcentaje son relativas y se basan en el tamaño del elemento contenedor. Por ejemplo, padding: 5%; establecerá el relleno en un 5% del ancho del elemento contenedor.

- **Em (em):** Las unidades "em" son relativas al tamaño de fuente actual del elemento. Si el tamaño de fuente es 16px y estableces margin: 1em;, el margen será igual a 16px.

- **Rem (rem):** Similar a "em", pero se basa en el tamaño de fuente del elemento raíz (generalmente el elemento <html>). Esto proporciona una forma más predecible de establecer espaciado relativo.

- **Centímetros (cm), milímetros (mm) y pulgadas (in):** Estas son unidades absolutas que se basan en medidas físicas reales. Por ejemplo, margin: 1cm; establecerá un margen de 1 centímetro.

- **Puntos (pt) y picas (pc):** Estas unidades absolutas son comúnmente utilizadas en diseño de impresión y tipografía. Un punto es aproximadamente 1/72 de pulgada, y una pica equivale a 12 puntos.

- **Viewport Width (vw) y Viewport Height (vh):** Estas unidades son relativas al tamaño de la ventana gráfica del navegador. Por ejemplo, width: 50vw; establecerá el ancho de un elemento al 50% del ancho de la ventana gráfica.

- **Viewport Minimum** (vmin) y Viewport Maximum (vmax): Estas unidades se basan en el tamaño mínimo o máximo de la ventana gráfica del navegador. height: 10vmin; establecerá la altura al 10% del valor más pequeño entre el ancho y el alto de la ventana.

- **Unidades fr:** Estas unidades se utilizan en diseño de cuadrículas (grid) y flexbox. Un "fr" representa una fracción del espacio disponible en un contenedor.

