# Curso de Html y CSS intensivo

## Html:

- ¿Que es Html? HyperText Markup Language. Es un lenguaje de marcado que permite maquetar una web
- Etiquetas: Son contendores de informacion como contenido, atributos, propiedades, etc.
- Atributos: Añaden informacion, modifican comportamiento de la etiqueta y contenido.

## Etiquetas basicas:

- h: Etiqueta basica para determinar semanticamente el tamaño de un texto.
  Pueden ser:

```
<h1></h1> - Mas grande
<h2></h2>
<h3></h3>
<h4></h4>
<h5></h5>
<h6></h6> - Mas pequeño
```

- p: Esta etiqueta permite definir descripciones, parrafos.

```
<p>Esto es un parrafo</p>
```

- span: Etiqueta en linea, permite mantener semantica en la web especialmente en los parrafos.

- listas: Existen las ordenadas "ol" y las desordenadas "ul".

```
<!-- Lista ordenada -->
<ol>
<li>Primero</li>
<li>Segundo</li>
</ol>

<!-- Lista desordenada -->
<ul>
<li>Cebolla</li>
<li>Tomate</li>
</ul>
```

- comentario:

```
<!-- Esto es un comentario -->
```

- a: Es una etiqueta que permite usarla para navegar mediante enlaces mediante el atributo "href".
  Existen los enlaces absolutos (Navegar a un sitio externo) y relativo (viajar a una ruta del propio proyecto)

```
<a href="https://www.google.com" target="_blank">Ir a goole</a>
```

- img: Etiqueta para imgen, cuenta con el atributo "src" que contiene el link del recurso, "alt" permite
  darle informacion a la imagen de forma interna en caso de no cargar.

- form: Permite crear formularios para el envio de informacion.

```
<!-- Formularios -->
<form>
<!-- Permite establecer un contenido para el input -->
<label>Nombre</label>
<input type="text" required />

<!-- Enviar informacion "submit" -->
<button type="submit">Enviar</button>
<!-- Restablecer formulario "reset" -->
<button type="reset">Restablecer</button>

<!-- Input para agregar imagen -->
<input type="file" />
</form>
```

## Etiquetas semanticas:

Permiten a que el codigo sea accesible y facil de entender y maquetar.

Estas pueden ser:

- header: Contiene titulos, logotipos, menus de navegacion.
- main: Contiene lo principal de la pagina, engloba lo importante.
- footer: Pie de pagina de la web. Incluye informacion de copyright, enlaces legales, contacto
- section
- article

## CSS:

- CSS: Cheat Sheet Style. Permite poder brindar estilos a la maquetacion, en forma de cascada

Propiedades basicas:

- color
- font-family
- font-size
- font-weight
- letter-spacing

## Formateo de pagina:

- margin (margen): Separacion del cuerpo de la web entre elementos
- border (borde): Borde del relleno
- padding (relleno): Se separa del contenido
- content (contenido)

## Distribucion de la Web:

Flex-box (caja flexible): Es el que se encarga del posicionamiento, distribucion de los elementos de nuestra web.
Algunos elementos de flex son:

- display: flex. Organiza los elementos tanto en filas de izquierda a derecha (row) como columnas (column) de arriba a abajo

## Position:

Permite manipular el poscionamiento de elementos en la web.
Tenemos:

- Relativa: Trabaja con las posiciones (top, right, bottom, left)
- Absoluta: Trabaja con el tamaño del elemento padre relativo (width, height)

## Maquetado:

Es el como se van a mostrar los elementos en pantalla

- grid (grilla): Permite trabajar de forma flexible con los elementos a mostrar en pantalla sin importar su tamaño, color, fuente, etc.

## Diseño responsivo:

- breakpoints: Cuando se diseña para pantallas los tamaños cambian, sus distribuciones.

Pantallas:

#### Movil:

- 360 x 800
- 390 x 844
- 393 x 873

#### Tablet:

- 768 x 1024
- 810 x 1080
- 820 x 1180

#### PC:

- 1920 x 1080
- 1536 x 864
- 1366 x 768