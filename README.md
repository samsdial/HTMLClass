# Que es Html

**El paso Inicial**
Es el lenguaje base para la web
- H		(Hyper)
- T		(Text)
- M	(Markup)(marcado)
- L		(Language)

Markup
- div
- section
- article
- span

## Hay lengujes 
- Interpretado
- Transpilado
Html es un lenguaje interpretado

## Hipertexto

Se basa en la vinculación de fragmentos textuales o gráficos a otros fragmentos o documentos.
[Haz Click](#foo)

## La Web
Es un conjunto de documentos HTML enlazados atraves de hipertextos

- URL -> Uniform Resource Locator
	-- 
- Http -> Hyper Text Transfer protocolo
	-- Es un protoco de transferencia de Hipertexto
- HTML -> Hypertext Markup Language 
	-- 

## Internet

Es toda la infraestructura de comunucación que perimite conectar todas las computadoras  atravez, claves, router, wifi, etc 
## ¿Cómo es HTML?

Markup
```html
<html>
	<head>
	</head>
	<body>
	</body>
</html>
```
# Historia del Html

[Tim Berners-Lee](https://es.wikipedia.org/wiki/Tim_Berners-Lee)
- 1989 Inicio del desarrollo
- 1991 lanzamiento de la web
- 1992 Lanzamiento de HTML
- 1994 Creación W3C
- 1998 HTML 4
- 1999 HTML 4.01 - XHTML
- 2004 WHATWG
- 2008 HTML 5
- 2014 Recomendación HTML 5
- 2016 HTML 5.1
- 2017 HTML 5.2

## HTML 5

Web Semántica
> El marcado tiene un significado, (div p y a) a (header, section, article)

Local Storage
> Acceso Offline

Acceso sin conexión al dispositivo

> Acceder al micrófono o la cámara

Web sockets

> Comunicación abierta bidireccional con el servidor 

Multimedia

> Video, audio

Gráficos (SVG, Canvas, WebGL)

> Avanzados con el navegador

Web workers

> Segundo proceso del navegador

CSS3 **
## W3C

Insititución internacional que genera recomendaciones y [estándares](https://es.wikipedia.org/wiki/Normalizaci%C3%B3n "Normalización") que aseguran el crecimiento de la _[World Wide Web](https://es.wikipedia.org/wiki/World_Wide_Web "World Wide Web")_ a largo plazo

Etapas de una Estándar:
- Working draft (WD) (1er Borrador)
- Candidate Recommendadtion (CR)
- Proposed recomendation (PR)
- Recomendación (REC)

# Los Navegadores
- 1993 Mosaic
- 1994 Netscape
- 1995 Internet Explorer
- 1996 Opera
- 2003 Safari
- 2004 Mozilla Firefox
- 2008 Google Chrome

# Estructura Intro

### Tag Opening and Closing

![alt text](https://www.aulaclic.es/html/graficos/sintaxis_html.svg) 

![alt text](https://cdo-curriculum.s3.amazonaws.com/media/uploads/html_element.png) 
### Self-Closing

```html
<img src="foto.jpg">
```
### Estructura Básica

```html
<!DOCTYPE html><!--Tipo de documento-->
<html lang="es"><!--Elemento principal (PAPA) // Atributo (El atributo lang especifica el idioma del contenido del elemento.)-->
    <head><!--insertar meta data -->
        <meta charset="utf-8"><!--Para indicar meta datos // Atributo Charset, este va a definir que tipo de caracteres vamos a utilizar en la web-->
        <title>Titulo</title><!--Titulo de la pagina Web--> 
    </head>
    <body><!--Contendido de la pantalla-->
        <h1>Hola mundo</h1>
    </body>
</html>
```
```html
<!DOCTYPE html>
<html lang="es">
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="description" content="Una genial descripción de mi primera pagina web">
        <title>Título mi primiera página web</title>
        <link rel="stylesheet" href="style.css"> 
        <link rel="shortcut icon" href="favicon.png"> 
    </head>
    <body>
        <h1>Título de mi página web</h1>
        <script src="script.js"></script>
    </body>
</html>
```

### Etiquetas Basicas
Heading encabezado
```html
<h1>Encabezado 1</h1>
<h2>Encabezado 2</h2>
<h3>Encabezado 3</h3>
<h4>Encabezado 4</h4>
<h5>Encabezado 5</h5>
<h6>Encabezado 6</h6>
```
```html
<header></header>
<nav></nav>
<article>
    <h1>Titulo</h1>
    <section>
        <h2>subtitulo</h2>
    </section>
</article>
<aside></aside>
<footer></footer>
```
# Que Programas

Editores de codigo:
    Visual Studio Code
    Atom
    Sublime 
ID Code
    Entorno de desarrollo integrado
    Android Studio Code
# Secciones en la web

```html
<header></header>
<nav></nav>
<article>
    <h1>Titulo</h1>
    <section>
        <h2>subtitulo</h2>
    </section>
</article>
<aside></aside>
<footer></footer>
```
### Los encabezados
El siguiente código muestra todos los niveles de encabezado.
```html
<h1>Heading level 1</h1>
<h2>Heading level 2</h2>
<h3>Heading level 3</h3>
<h4>Heading level 4</h4>
<h5>Heading level 5</h5>
<h6>Heading level 6</h6>
```
El código siguiente muestra unos pocos encabezados con algo de contenido debajo de ellos.
```html
<h1>Heading elements</h1>
<h2>Summary</h2>
<p>Some text here...</p>

<h2>Examples</h2>
<h3>Example 1</h3>
<p>Some text here...</p>

<h3>Example 2</h3>
<p>Some text here...</p>

<h2>See also</h2>
<p>Some text here...</p>    
```
Que no hacer:
```html
<h1>Cabecera nivel 1</h1>
<h3>Cabecera nivel 3</h3>
<h4>Cabecera nivel 4</h4>
``` 
Importante Anidar
```html
<h1>1. Harry Potter</h1>
    <article>
    <h2>1.1 Sinopsis</h2>
    <h2>1.2 Novelas</h2>
        <section>      
            <h3>1.2.1 Harry Potter y la Piedra Filosofal</h3>
        </section>
    <h2>1.3 Películas</h2>
        <section>
            <h3>2.3.1 Harry Potter y la Piedra Filosofal</h3>
        </section>
    </article>

``` 
# Agrupación de contenido
### Listas ordenadas y desordenadas
ul Under list
li list item
ol Orden list
```html
<ul>
    <li>Item</li>
    <li>Item</li>
    <li>Item
        <ol>
            <li>SubItem</li>
            <li>Item</li>
        </ol>
    </li>
</ul>
``` 
### Lista de definicion
Termino y Definición
dl: Definition list
dt: Definition term
dd: Definition description
```html
<dt>
    <dt>Peru</dt>
    <dd>lima</dd>
</dt>
``` 
### Figure y FigCaption

```html
<figure>
    <pre>
        <code>
            function hola (){
                return "hola"
            }
        </code>
    </pre>
    <figcaption>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Facere in voluptates voluptatum!
    </figcaption>
</figure>
``` 

### Otros Elementos

main: Representa el contenido principal del 
p: parrafo
hr: Horizontal Rule
pre: preformat
blockquote: Crea citas en bloque, marca las citas a otros autores o documentos.

```html
<main>
    <p>Este parrafo</p>
    <hr>
    <pre>
        Este texto
            se presentará igual
        en el navegador
    </pre>
    <blockquote>
        Usar blockoute para destacar citas.
    </blockquote>
</main>
``` 
### Divisiones (layout)
div: 
```html
<div class="user">
    <div class="user_name">
        <p>Alexys</p>
    </div>
    <div class="user_image">
        <img src="alexys.png" alt="Foto de alexys">
    </div>
</div>
``` 

# Practica: Agrupación de contenido
# Elementos inline y de bloque
# Enlaces
# Marcadores
# Imagenes
# Viewport y devive pixel ratio
# Atributo srcset
# Microdatos y Open Graph
# Tablas
# Agrupar Tablas
# Formularios
# Tipos de Input
# Campos de Seleccion y atributos
# Video y Codecs En Html
