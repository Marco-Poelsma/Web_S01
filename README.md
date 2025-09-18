# SESIÓN 1

[Pulsa aquí si quieres ir al ejercicio de clase](https://github.com/Marco-Poelsma/S01-Ex)

## Herramientas Básicas

Para web, usaremos Visual Studio Code para programar y Google Chrome (u otro navegador según nuestra preferencia) para ver lo que hacemos.

Para ayudarnos con ver las páginas que usamos, usaremos algunas extensiones:
- Prettier - Code Formatter
- HTML Hint
- vscode-icon
- Live Server

## Internet:

Internet es una red de redes, donde podemos conectar dispositivos para que se comuniquen entre ellos o para encontrar información.

La arquitectura básica de internet es la arquitectura cliente-servidor. En este tipo de estructura, hay un cliente (controlado por un usuario), que se conecta directa o indirectamente a un servidor, que proporciona información.

## Configuración del entorno:

Es importante tener la extensión "Live Server". Esta nos permite montar un servidor en 127.0.0.1:5500.

El archivo base de HTML es index.html. Es importante solo usar ese nombre por el momento.

## Tags de inicio de HTML:

### \<\!DOCTYPE html\>

Este tag nos indica el tipo de documento (en este caso, HTML).

### \<html\>

Es el tag que incluye todo el contenido (encabezado y cuerpo) de la página. Se cierra con \<\/html\>.

Es importante indentar todos los elementos para que quede ordenado y legible.

### \<head\>

Incluye los metadatos de nuestra página. Es decir, información que no se puede leer, como el lenguaje, la codificación de los carácteres (texto), el título de la pestaña, enlaces a hojas de estilos (CSS) y scripts (JS), etc.

### \<!-- --\>

Comentarios.

### \<h1\>, \<h2\>, \<h3\>, \<h4\>, \<h5\>, \<h6\>

Títulos. El \<h1\> es el más importante (grande) y \<h6\> el menos importante.

### \<p\>

Texto normal.

### \<strong\>

Nos permite hacer palabras en negrita. Es importante recordar que este tag (al igual que los tags de título) tiene significado semántico. Por eso, es importante solo usar estos tags para partes que realmente queramos recalcar.

### \<a\>

a de **anchor**. Sirve para añadir enlaces a otras páginas. El enlace se añade dentro del tag, con el atributo href.

### \<img /\>

Sirve para añadir imágenes. Requiere el atributo src. Este tag también es uno de los pocos que se autocierra, es decir, no requiere un tag de cierre.

### \<ul\> y \<ol\>

Lista desordenada (\<ul\>) u ordenada (\<ol\>). Dentro de las listas, se añaden nuevos elementos con el tag \<li\>.

## Aprender más
MDN (Mozilla Developer Network) es una página donde podemos aprender más sobre todos los elementos y sus atributos.