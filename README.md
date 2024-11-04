# Curso Definitivo de HTML y CSS

**Tabla de Contenido**
- [Curso Definitivo de HTML y CSS](#curso-definitivo-de-html-y-css)
    - [Qué aprenderás sobre HTML y CSS 1/55](#qué-aprenderás-sobre-html-y-css-155)
    - [¿Qué es el Frontend? 2/55](#qué-es-el-frontend-255)
      - [Herramientas que maneja un frontend](#herramientas-que-maneja-un-frontend)
    - [¿Qué es Backend? 3/55](#qué-es-backend-355)
    - [¿Qué es Full Stack? 4/55](#qué-es-full-stack-455)
    - [Páginas Estáticas vs. Dinámicas 5/55](#páginas-estáticas-vs-dinámicas-555)
    - [HTML: anatomía de una página web 6/55](#html-anatomía-de-una-página-web-655)
    - [Index y su estructura básica: head 7/55](#index-y-su-estructura-básica-head-755)
    - [Index y su estructura básica: body 8/55](#index-y-su-estructura-básica-body-855)
      - [Etiquetas del cuerpo del documento (body):](#etiquetas-del-cuerpo-del-documento-body)
    - [Reto: crea tu lista de compras del supermercad 9/55](#reto-crea-tu-lista-de-compras-del-supermercad-955)
    - [Anatomía de una etiqueta de HTML 10/55](#anatomía-de-una-etiqueta-de-html-1055)
    - [Tipos de imágenes 11/55](#tipos-de-imágenes-1155)
      - [Tipos de imágenes para web](#tipos-de-imágenes-para-web)
      - [Formatos de imagen para web](#formatos-de-imagen-para-web)
    - [Optimización de imágenes 12/55](#optimización-de-imágenes-1255)
    - [Etiqueta img 13/55](#etiqueta-img-1355)
    - [Etiqueta figure 14/55](#etiqueta-figure-1455)
    - [Etiqueta video 15/55](#etiqueta-video-1555)
    - [Etiqueta form e input 16/55](#etiqueta-form-e-input-1655)
    - [Calendar 17/55](#calendar-1755)
    - [Autocomplete y require 18/55](#autocomplete-y-require-1855)
    - [Select 19/55](#select-1955)
    - [Input type submit vs. Button tag 20/55](#input-type-submit-vs-button-tag-2055)
    - [¿Qué es CSS? 21/55](#qué-es-css-2155)
    - [¿Cómo utilizamos CSS?: por etiqueta, selector, class y por ID 22/55](#cómo-utilizamos-css-por-etiqueta-selector-class-y-por-id-2255)
      - [Cómo utilizar CSS en la hoja de estilos?](#cómo-utilizar-css-en-la-hoja-de-estilos)
    - [Pseudo clases y pseudo elementos 23/55](#pseudo-clases-y-pseudo-elementos-2355)
    - [Anatomía de una regla de CSS 24/55](#anatomía-de-una-regla-de-css-2455)
    - [Modelo de caja 25/55](#modelo-de-caja-2555)
    - [Herencia 26/55](#herencia-2655)

---
### Qué aprenderás sobre HTML y CSS 1/55
Existen tres estándares importantes para generar productos web. Estos son los lenguajes o estándares que entiende todo navegador web:

- HTML
- CSS
- JavaScript

**HTML**

Estructura de los documentos que se visualizan en los navegadores (Chrome, Edge, Firefox, Safari, Opera, entre otros). Es el lenguaje con el que clasificamos o etiquetamos cada parte del documento, dejándole saber al navegador qué información va a visualizar y qué valor tiene para nosotros. De esa manera, presentamos: Barras de Navegación, Secciones, artículos, listas, títulos de diferentes tamaños, audios, videos, imágenes, entre otros.

**CSS**

Es el lenguaje con el que le damos estilos a todo el contenido previamente etiquetado con HTML. Es el encargado o usado para darle todo el aspecto visual de manera profesional, usando estándares de diseño de documentos y logrando así la correcta visualización de textos y recursos audiovisuales en formatos digitales o, en nuestro caso, las páginas web.

**JavaScript**

Es lenguaje que se emplea para crear o brindar a las páginas web la capacidad de interactuar con el usuario y los recursos asociados a una página web, como lo son: bases de datos, servidores de diversa índole, información derivada de la interacción de cada página en sí.

**Diferencias entre HTML, CSS y JavaScript**

- HTML es la estructura, como si fuese el esqueleto de un ser humano o los cimientos de un edificio. Por ejemplo: una página web que funciona, pero sin interactividad, colores ni diseño.
 
- CSS corresponde a lo estético, como la piel de ser humanos. La pintura y adornos de los edificios o la manera en que es posible que la estructura del html se vea mejor para los usuarios.

- JavaScript equivale a los músculos, lo que da esa interactividad a las personas para moverse y realizar acciones como correr.

![](https://static.platzi.com/media/user_upload/css%20html%20js-c5cad547-d054-48d7-83be-bc2caee99577.jpg)

---
### ¿Qué es el Frontend? 2/55

**Framework** es un frangmento de algo pre-hecho por ejemplo un **Framework de CSS** es una herramienta que trae fragmentos de CSS ya construidos, los frameworks vienen con cosas pre-hechas.

**Frontend** es la parte de un programa o dispositivo a la que un usuario puede acceder directamente. Son todas las tecnologías de diseño y desarrollo web que corren en el navegador y que se encargan de la interactividad con los usuarios.

Un **programador Frontend** debe saber de código que entienda el navegador (HTML, CSS y JavaScript) para poder usar algunos frameworks o librerías que expanden sus capacidades para crear cualquier tipo de interfaces de usuarios. React, Redux, Angular, Bootstrap, Foundation, LESS, Sass, Stylus y PostCSS son algunos de ellos.

#### Herramientas que maneja un frontend

Debido a que un frontend es el desarrollador que va a manejar las cosas del lado del cliente, las tecnologías con las que va a trabajar son:

- HTML: https://devdocs.io/html/
- CSS: https://devdocs.io/css/
- JavaScript: https://devdocs.io/javascript/

**Frameworks de CSS para frontend:**

- Bootstrap: https://getbootstrap.com/
- Foundation CSS: https://get.foundation/
- Materialize CSS: https://materializecss.com/

**Los frameworks de JavaScript para frontend:**

- React JS: https://es.reactjs.org/
- Angular JS: https://angular.io/
- Vue JS: https://vuejs.org/

**Preprocesadores de CSS:**

- Stylus: https://stylus-lang.com/
- SASS: https://sass-lang.com/

**Compiladores / empaquetadores de JS:**

- BABEL: https://babeljs.io/
- Webpack: https://webpack.js.org/

---
### ¿Qué es Backend? 3/55

**Backend** en programación corresponde al lado opuesto a un Front-end en un sitio web o aplicación, ya que el Backend trabaja en el lado del servidor, mientras el Frontend lo hace en el lado del cliente. Es el responsable de **manejar toda la lógica** que hay detrás de una petición dada por el navegador hacia el servidor.

Una característica que lo diferencia del Frontend es que no tiene estándares, puesto que tiene varios lenguajes de programación (Node.js, Python, PHP, Ruby, GO, Java, .NET entre otros) con los que debe trabajar. Cada uno de estos lenguajes tiene sus propios frameworks como:

- Django (Python)
- Lavarel (PHP)
- Rails (Ruby)
- Express (JavaScript)
- Spring (Java)

El Backend también tiene en cuenta la infraestructura donde va a realizarse el deploy de su aplicación (esto también puede ser tarea de un DevOps, un perfil dedicado a la infraestructura), con tecnologías como:

- Google Cloud
- DigitalOcean
- AWS
- Heroku, entre otras.

**¿Qué es deploy?**

Deploy es un término famoso entre los desarrolladores web. Puede significar muchas cosas, dependiendo del ambiente y de la tecnología usada. Sin embargo, los significados que más se refieren a la práctica y pueden resumir su función son: implantar, colocar en posición, habilitar para uso o, simplemente, publicar.

Por último, entramos en bases de datos, que son las encargadas de almacenar toda la información del proyecto. Los principales tipos son:

- Bases de datos relacionales (como MySQL)
- Bases de datos no relacionales (como mongoDB).

---
### ¿Qué es Full Stack? 4/55

**Full Stack** es un término utilizado para describir a los desarrolladores que conocen tanto los lenguajes de frontend como de backend. Principalmente, el desarrollo full stack se refiere al uso de JavaScript en el backend y de HTML/CSS/JavaScript en el frontend para crear nuevas plataformas.

![](https://static.platzi.com/media/user_upload/HTML-e19c2528-ea5a-4f96-8a61-b518452a7be6.jpg)

El nacimiento de tecnologías que funcionan entre el frontend y el backend ha dado lugar a la proliferación de frameworks y herramientas de desarrollo “full stack”, que permiten a los desarrolladores construir sus propias aplicaciones web completas empleando un único lenguaje de programación como Django para Python.

**Qué es un desarrollador Full Stack**

Las y los **desarrolladores Full Stack** son profesionales que se encargan tanto de la parte visual y de interacción de un sitio (frontend), como de su lógica y funcionamiento del lado del servidor (backend).

Un stack (en inglés: pila o montón) se refiere al grupo de tecnologías que componen un sitio web en todos los aspectos (desde la base de datos, hacia el manejo lógico y la interfaz visual). Una o un **desarrollador Full Stack** en teoría es capaz de manejar la pila completa de un sitio, tanto de frontend como de backend, además sabe utilizar su base de datos.

![](https://static.platzi.com/media/user_upload/habilidadesfullstack-cb788cc9-eaf6-40fb-a517-f10761010b76.jpg)

**Qué hace un desarrollador Full Stack**

Una desarrolladora o **desarrollador Full Stack** entiende muy bien cómo funciona un producto web de principio a fin, desde su diseño en mockup y deploy hasta producción.

Este tipo de programador o programadora no maneja por completo todas las tecnologías de ambas partes, pues cada una requiere conocimiento profundo. De hecho, no es recomendado profundizar en tantas especialidades y no es sano. El desarrollo web evoluciona muy rápido y cada dos o tres meses encontrarás algo nuevo.

**Cómo ser un desarrollador Full Stack**

Para convertirse en Full Stack developer debes dominar las dos áreas básicas: [backend y frontend](https://platzi.com/blog/que-es-frontend-y-backend/). Esto te ayudará a comprender cómo funciona cada uno y a generar una comunicación entre sí. La mayoría de la interacción entre estos dos mundos se basa en consumo de API y comprender cómo consumir una API desde el Frontend te ayudará a entender a cómo construir una API desde el Backend.

Además, aprender de las diferentes formas que tenemos de subir en internet una aplicación web te ayudará a entender las diferentes estrategias de deploy que existen y te permitirá ampliar tus conocimientos en el mundo del desarrollo web.

**Tecnologías Full Stack para desarrolladores**

Aprender un stack conocido puede ayudarte a dar tus primeros pasos como desarrollador Full Stack y a escalar un proyecto a producción de una manera más rápida y con una mayor interacción. Para eso necesitas estas herramientas.

- LAMP (Linux, Apache, MySQL, PHP)

![](https://static.platzi.com/media/user_upload/LAMP-f74468e0-6f25-4990-ab3a-4a3b323f44f9.jpg)

- MERN (MongoDB, Express.js, React, Node)
- PERN (PostgreSQL, Express.js, React, Node)

![](https://static.platzi.com/media/user_upload/tecnologiasfullstack-732fde16-557a-4927-ace2-b5f39bc873a5.jpg)

---
### Páginas Estáticas vs. Dinámicas 5/55

Los sitios web se comportan de forma diferente dependiendo de la forma en que fueron diseñados desde su concepción, tomando en cuenta la interacción con el usuario. Aquí veremos las diferencias entre sitios web estáticos y dinámicos:

**Sitos Web Estáticos**

La información que contiene se mantiene constante y estática. No se actualiza con la interacción del usuario. Es conveniente para realizar landing pages (páginas informativas o de aterrizaje) o blogs. Se mostrarán siempre iguales para todos los usuarios.

**Sitios Web Dinámicos**

También conocidos como **aplicaciones web o Web Apps**, actualizan su información con respecto a la interacción del usuario. Dependen de una base de datos, de donde extrae e ingresa información. Serán diferentes, dependiendo del usuario que la use y la información que se ingrese.

Ejemplo de páginas estáticas:

- Menú de un restaurante
- Blog de viajes
- Página informativa de un negocio

Ejemplo páginas dinámicas:

- Sistema de reporte de ventas
- Linkedin
- Banca en línea

---
### HTML: anatomía de una página web 6/55

HTML (HyperText Markup Language) es un lenguaje de marcado de texto. Se utiliza para darle una estructura al sitio web que estás visitando.

**Estructura básica de HTML en una página Web**

- Container: contenedor principal
- Header: cabecera de la página. Aquí usualmente encuentras el logo y el menú de navegación del sitio.
- Main content: estructura principal. Por ejemplo, el feed o lista de publicaciones de una red social.
- Sidebar: contenido secundario de una página, que usualmente se encuentra a los lados del contenido principal (o main).
- Footer: pie de página. Esto se encuentra al fondo del sitio web, salvo en casos de sitios web donde el scroll (o navegación hacia abajo) es infinito, por ende, no tendría sentido ponerlo al fondo.

![](https://static.platzi.com/media/user_upload/Captura%20de%20pantalla%20%2817%29-f08bb2df-26d7-4221-aebc-c84dd0b015e1.jpg)

Las etiquetas en HTML nos ayudan a diferenciar en qué parte del contenido nos encontramos.

La web se conforma de tres conceptos:

- URL: Uniform Resource Locator. El identificador único del sitio en el navegador (por ejemplo: https://platzi.com).
- HTTP: Protocolo de transferencia de hipertexto. Es el estándar que se utiliza para enviar datos a través de paquetes entre el cliente y el servidor.
- HTML: es el código que se emplea para estructurar el contenido de tu web, y darle sentido y propósito.

HTML son siglas que corresponden a Hyper Text Markup Language (Lenguaje de Marcado de Hipertexto).

- Hyper Text significa que el texto tiene interactividad, conexión con otros documentos.
- Markup significa que le pone etiquetas a los elementos. Por eso también se le conoce como un lenguaje de etiquetas.

HTML es un lenguaje interpretado. Además, HTML es un estándar, así que no importa desde qué navegador o dispositivo se ejecute, el código sigue siendo el mismo en cualquier sitio.

---
### Index y su estructura básica: head 7/55

El primer archivo de mi proyecto siempre debe llamarse index.html porque el navegador va a buscar ese archivo, de otra forma tendría que indicarle al navegador cuál es el archivo que debe abrir.

```
<!-- La etiqueda DOCTYPE html sirve para decirle al navegador
que está leyendo html 5 y que debe interpretar todo como html 5 -->
<!DOCTYPE html>

<!-- La etiqueda html delimita todo el proyecto, todo estará dentro de ella -->
<!-- lang es un atributo que indica el idioma que tiene el proyecto al navegador -->
<html lang="es">
    <head>
        <meta charset="UTF-8" />

        /* el atributo description sirve para dar información sobre la 
        página cuando se busca en internet */
        <meta name="description" content="Esta página te mostrará fotos de gatos" />

        /* el atributo robots sirve para que los robots en internet tengan
        acceso a nuestra página y puedan buscarla como por ejemplo el robot de
        google o de algún otro buscador, se utiliza luego el atributo 
        content="index, follow" para que puedan hacerlo, si quisieramos que no
        lo hicieran seria unfollow*/
        <meta name="robots" content="index,follow" />
        <title>Es mi página</title>

        /* el meta viewport sirve para que la página web pueda escalar
        con la pantalla que tenga el usuario ya sea una computadora o
        un telefono*/ 
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />

        /* la etiqueta link sirve para agregar nuestro css al html,
        el atributo rel sirve para decirle que es una hoja de estilos y href sirve
        para decirle donde se encuentra esa hoja de estilos */
        <link rel="stylesheet" href="./css/style.css">
    </head>
    <body>

    </body>
</html>
```

---
### Index y su estructura básica: body 8/55

Semántica de HTML:

![](https://by3301files.storage.live.com/y4mK_79AMLj-NLSyxmc5npEb148uWsa9C9GXkGprk5TVUnjlnLzSUij8gvn9icuhWZWAJB8jowuu4XfhL_H58PjXujxcJYZu-C-Xyqy6466mTWYvXnTO5p0riEUoi2J7jIY8FBRSnBaPiL_RGNW0_i55zduSgzSLe9s-cit-SVJHWpYD01qn959fRRieA58S44SHW-xMn0AQGCdykwvN6nCkGt8UmWCL_zlDQZvQfFffZ0?encodeFailures=1&width=417&height=717)

***body*** es la etiqueta que identifica la parte visible de nuestro sitio web. Dentro del body, se añadirán las etiquetas para marcar los elementos visuales del sitio web, como logotipo, menús de navegación, contenido principal, entre otrs. Es muy importante usar HTML semántico y no llenar todo de `<div>` para que nuestro sitio sea mejor interpretado por el navegador y, por lo tanto, más accesible.

#### Etiquetas del cuerpo del documento (body):

- article: diferencia partes del contenido que pueden vivir por sí mismas.
- nav: para hacer menús de navegación.
- aside: contenido menos relevante, como publicidad, etc.
- section: sirve para diferenciar las secciones principales del contenido.
- header: cabecera del documento.
- footer: pie de página del documento.
- h1 - h6: títulos de nuestro sitio web.
- table: tablas de contenidos, similar a la estructura de las hojas de calculo.
- ul y ol: listas de items.
- div: cualquier división para organizar el contenido.
- h1 a h6: son etiquetas para indicar títulos con un estilo que destaca del resto.
- article: es la parte de nuestro contenido que puede vivir por sí mismo. Pueden haber tantos artícle como proyectos o eventos tenga nuestro portafolio.
- p: define el texto de un párrafo.
- small: aplica una apariencia de texto reducido en tamaño.
- strong: aplica al texto un formato de negritas.
- a: corresponde a un ancla o enlace a una url interna o externa del documento.
- img: con esta etiqueta podemos enlazar imágenes en el documento.
- figure: le da un contexto semántico a las imágenes.

**Ejemplo de un body con etiquetas semánticas HTML:**

~~~
  <body>

    <header> <!--Sección superior de nuestro website--> 

      <nav></nav> <!--Sección de navegación de nuestro website, siempre dentro del header-->

    </header>

    <main> <!--Main es el contenido central de nuestro website, "la parte del medio"-->

      <section> 
        <!--Nuestro website puede estar divido por secciones, por ejemplo platzi tiene 3: El navegador de cursos y rutas, el feed y nuestras rutas de aprendizaje-->

        <article>
          <!--Contenido independiente de la página. Es reutilizable-->
        </article>

      </section>

      <ul> <!--Lista desordenada: Sin numerar-->

        <li><!--Item List. Elementos de la lista--></li>

      </ul>

      <ol></ol> <!--Lista ordenada: Numerada-->
      
    </main>

    <footer> <!--Sección final de nuestro website-->

    </footer>

    <p>Soy un texto</p> <!--Párrafo, texto-->

    <h1>Soy un titulo</h1> 
    <!--Títulos, muestran el texto más grande y con negrilla. Existen desde el h1 al h6-->

    <a href="#">Soy un link</a>
    <!--Enlaces/links que nos permitirán movernos entre páginas.-->

  </body>
~~~

---
### Reto: crea tu lista de compras del supermercad 9/55

~~~
<h1>Lista para el súper</h1>
<ul> <!-- La etiqueta ul crea una lista desordenada -->
  <li>Frutas</li> <!-- li lleva los elementos de la lista -->
  <ol> <!-- ol crea una lista ordenada -->
    <a href="https://www.google.com/search?client=opera&q=pai+de+manzana&sourceid=opera&ie=UTF-8&oe=UTF-8" target="_blank"><li>manzana</li></a>
    <a href="https://www.google.com/search?q=magu+de+platano&client=opera&hs=CuN&sxsrf=ALiCzsZ9tx9owq81vOh6eZYX3GaZ4yRCSA%3A1658521705474&ei=aQjbYvioHKLYkvQP1ICpoAE&ved=0ahUKEwi4ge3oqo35AhUirIQIHVRAChQQ4dUDCA0&uact=5&oq=magu+de+platano&gs_lcp=Cgdnd3Mtd2l6EAMyBAgAEA0yBAgAEA0yBAgAEA0yBggAEB4QDTIICAAQHhANEAoyBggAEB4QDTIGCAAQHhANMgYIABAeEA0yBggAEB4QDTIGCAAQHhANOgcIABBHELADOgcIABCwAxBDOgwILhDIAxCwAxBDGAE6BAgjECc6BQgAEJECOggILhDUAhCRAjoLCC4QgAQQxwEQ0QM6BQgAEIAEOgUILhCABDoFCC4QkQI6BwguEIAEEAo6BwgAEAoQywE6BQguEMsBOgcIABCABBAKOgUIABDLAToHCC4QChDLAToLCC4QgAQQxwEQrwFKBAhBGABKBAhGGABQrh9YiTpg1DtoBHABeACAAaYBiAGEEJIBBDAuMTaYAQCgAQHIAQvAAQHaAQQIARgI&sclient=gws-wiz" target="_blank"><li>Plátano</li></a>
    <a href="https://www.google.com/search?client=opera&q=jugo+de+limon&sourceid=opera&ie=UTF-8&oe=UTF-8" target="_blank"><li>Limón</li></a>
  </ol>
  <li>Carnes</li>
  <ol>
    <a href="https://www.google.com/search?q=pollo+al+carbon+receta&client=opera&hs=KM3&sxsrf=ALiCzsZ-uSvLBEm_ZMYF-KMWxR8xHeimzw%3A1658522171736&ei=OwrbYobWK_aykvQPzautwAc&oq=pollo+al+carbon+rece&gs_lcp=Cgdnd3Mtd2l6EAMYADIFCAAQywEyBQgAEMsBMgYIABAeEBYyBggAEB4QFjIGCAAQHhAWMgYIABAeEBYyBggAEB4QFjIGCAAQHhAWMgYIABAeEBYyBggAEB4QFjoHCAAQRxCwAzoKCAAQRxCwAxDJAzoICAAQkgMQsAM6DAguEMgDELADEEMYAToSCC4QxwEQrwEQyAMQsAMQQxgBOg8ILhDUAhDIAxCwAxBDGAE6EgguEMcBENEDEMgDELADEEMYAToHCAAQyQMQQzoFCAAQkgM6BAgAEEM6BQgAEIAEOggIABDJAxDLAUoECEEYAEoECEYYAFC-CFj7DmCEGmgBcAF4AIABeYgBwwSSAQMwLjWYAQCgAQHIAQ3AAQHaAQQIARgI&sclient=gws-wiz" target="_blank"><li>Pollo</li></a>
    <a href="https://www.google.com/search?q=carne+molida+para+hamburguesa&client=opera&hs=8gi&sxsrf=ALiCzsaptZ6-rYpC1k33ihPnS7yYRErjMw%3A1658522178937&ei=QgrbYo_rOIyNwbkPhv2BiAk&oq=carne+molida+para+am&gs_lcp=Cgdnd3Mtd2l6EAMYADIHCAAQChDLATIGCAAQHhAWMgYIABAeEBYyCggAEB4QDxAWEAoyCAgAEB4QFhAKMgYIABAeEBYyBQgAEIYDMgUIABCGAzoHCAAQRxCwAzoHCAAQsAMQQzoECCMQJzoICC4Q1AIQkQI6BQguEJECOgsILhCABBDHARDRAzoFCAAQgAQ6BQgAEJECOgQIABBDOgQILhBDOgUILhCABDoLCC4QgAQQxwEQrwE6CggAEIAEEIcCEBQ6BQgAEMsBOgUILhDLAToICAAQHhAPEBZKBAhBGABKBAhGGABQ_gpYpEFgtUxoA3ABeACAAZEBiAHHEpIBBDAuMjCYAQCgAQHIAQnAAQE&sclient=gws-wiz" target="_blank"><li>Carne molida</li></a>
  </ol>
  <li>Verduras</li>
  <ol>
    <a href="https://www.google.com/search?q=carrot+juice&client=opera&hs=0M3&sxsrf=ALiCzsZfs7UPVhBrYt1WP42cueTUqN8a9g%3A1658522213392&ei=ZQrbYsS6F5KHkvQP8MW3uAg&ved=0ahUKEwiEgYbbrI35AhWSg4QIHfDiDYcQ4dUDCA0&uact=5&oq=carrot+juice&gs_lcp=Cgdnd3Mtd2l6EAMyBQguEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCC4QgAQyBQgAEIAEOgcIABBHELADOgQIIxAnOggILhDUAhCRAjoFCC4QkQI6CwguEIAEEMcBENEDOgUIABCRAjoNCC4QgAQQxwEQ0QMQCjoECC4QQzoKCAAQgAQQhwIQFDoFCAAQywE6CAgAEMkDEMsBOgUIABCSA0oECEEYAEoECEYYAFDFFFiYJmDxJmgDcAF4AIAB_wGIAcUMkgEFMC45LjKYAQCgAQHIAQjAAQE&sclient=gws-wiz" target="_blank"><li>Zanahoria</li></a>
  </ol>
</ul>
~~~

---
### Anatomía de una etiqueta de HTML 10/55

Una etiqueta HTML puede tener tantos atributos como desees, y cada atributo tiene su propia función. En el siguiente ejemplo, veremos la forma en la que se compone una etiqueta HTML:

![Anatomia de una etiqueta](https://i.postimg.cc/k4s9SqbT/Anatom-a-de-Etiqueta.png)

![Tag anatomy](https://static.platzi.com/media/user_upload/anatomia%20de%20html-fc475d3a-6d91-41b5-a893-ee4790dcb637.jpg)

- No todas las etiquetas llevan una etiqueta de cierre. Las que llevan un cierre son aquellas que albergan un contenido que nos dice a dónde nos va a llevar (nombre de la página, nombre del link).
- Lo que va dentro de la etiqueta de apertura es un atributo (nombre del atributo = href y el valor del atributo es la url).
- El contenido + la etiqueta = Elemento

---
### Tipos de imágenes 11/55

Las imágenes representan una pieza fundamental al momento de mostrar contenido para web. Aquí conoceremos los principales tipos de imágenes web y sus formatos.

#### Tipos de imágenes para web

**Lossless (sin pérdida):**

- Capturan todos los datos del archivo original.
- No se pierde nada del archivo original.
- Puede comprimirse, pero podrá reconstruir su imagen al estado original

**Lossy (con pérdida):**

- Se aproximan a su imagen original.
- Podría reducir la cantidad de colores en su imagen o analizar la imagen en busca de datos innecesarios.
- Por consiguiente puede reducir su tamaño, lo que mejora el tiempo de carga de la página, pero pierde su calidad.
- Los archivos tipo lossy son mucho más livianos que los archivos tipo lossless, por lo que son ideales para usar en sitios en donde el tamaño del archivo y la velocidad de descarga son importantes.

![](https://static.platzi.com/media/user_upload/table%20for%20diferent%20images-42fdf349-a492-4ff5-afbd-1f437c804e4a.jpg)

#### Formatos de imagen para web

- **GIF** (Graphics Interchange Format): Formato de imagen sin pérdida, no se puede comprimir
- **PNG 8** (Portable Network Graphics): Formato de imagen sin pérdida, uso de colores de 256, se utiliza para logotipos e iconos para la página.
- **PNG 24** (Portable Network Graphics): Formato de imagen sin pérdida, utilización de colores ilimitados, alta calidad, si intentamos comprimir no ayudará demasiado por la gran cantidad de colores.
- **JPG / JPEG** (Photographic Experts Group): Formato de imagen con pérdida, perdemos calidad a la hora de comprimirlas, pero llegan a ser óptimas para la carga en la página web.
- **SVG - Vector** (Scalable Vector Graphics): Formato de imagen muy ligero sin pérdida, con svg no perdemos calidad, ya que está compuesta por vectores.
- **WebP**: Es un formato gráfico en forma de contenedor que sustenta tanto compresión con pérdida como sin ella. ​​Fue desarrollado por Google.

---
### Optimización de imágenes 12/55

Una imagen en la web en promedio debe pesar 70Kb.

**Opciones para trabajar las imágenes**

- Mejora el tamaño de tus imágenes
  - [Tiny PNG](https://tinypng.com) funciona para jpg y para png.

- Retira metadatos de tus imágenes
  - [Verexif](https://www.verexif.com) normalmente usada para imagenes tomadas con cámaras o teléfonos.

---
### Etiqueta img 13/55

El elemento HTML `<img>` incrusta una imagen dentro de un documento. A continuación, veremos cómo funciona.

La etiqueta `<img>` va siempre dentro del contenedor `<body>`, pues es un elemento visible.

***Funcionamiento de la etiqueta alt:***

`<img src=“ubicación de la imagen” alt=“descripción de la imagen”>`

Con esta misma estructura, podemos utilizar el siguiente ejemplo de un estudiante cansado:

`<img src=“https://www.ipp.edu.pe/blog/wp-content/uploads/2020/05/shutterstock_1489158410.jpg” alt=“estudiante cansado”>`

Al añadir el código que acabamos de crear a un documento, la imagen que se mostrará en el navegador es la siguiente:

![](https://www.ipp.edu.pe/blog/wp-content/uploads/2020/05/shutterstock_1489158410.jpg)

**Atributos de la etiqueta img**

La etiqueta img cuenta con dos atributos, el atributo “src” y el segundo atributo es “alt”. Ambos son importantes.

El atributo de “src” es para mostrar en dónde se encuentra la imagen que vamos a incrustar. Las imágenes se pueden obtener de alguna carpeta o una URL que obtengamos de internet.

  - En caso de que el nombre de tu imagen lleve algún espacio, deberás sustituir ese espacio con un guion o guion medio. Caso contrario, el navegador no podrá reconocer la ubicación.

alt sirve para agregar una descripción a nuestra imagen. Esto es útil por cuestiones de SEO y también para accesibilidad (por ejemplo para personas con visión reducida).

  - `<img/>`, a diferencia de la gran mayoría de las demás etiquetas de HMTL, no necesita una etiqueta de cierre.

Imágenes gratuitas que se pueden descargar por tamaños en [Pexels](https://www.pexels.com/es-es/).

---
### Etiqueta figure 14/55

`Figure` es una etiqueta que permite almacenar una imagen en su interior. Es una mejor práctica comparada con usar solamente un contenedor `div`. Como complemento al contenedor `figure`, se utiliza la etiqueta `figcaption` 
, que permite darle una pequeña descripción a la imagen, como el autor, fuente o algo por el estilo, que se mostrará usualmente abajo de la imagen.

`Figcaption` se diferencia del atributo `Alt` porque esta última muestra su descripción en texto en el navegador solamente cuando no hay una imágen.

Es importante considerar que la etiqueta figure no es únicamente para imágenes:

[El elemento HTML](https://platzi.com/clases/1802-accesibilidad-web/26072-que-es-el-html-semantico-y-por-que-es-importante/) representa contenido independiente, a menudo con un título. Por lo general, se trata de una imagen, una ilustración, un diagrama, un fragmento de código, o un esquema al que se hace referencia en el texto principal, pero que se puede mover a otra página o a un apéndice sin que afecte al flujo principal.

**Ejemplo de etiqueta Figure:**

```
<figure>
  <img
  src="./pics/tinified/small.jpg"
  alt="Es una imagen de un perrito"
  />
  <figcaption>Es una imagen de un perritofigcaption>  
figure>
```

<figure>
  <img
  src="./pics/tinified/small.jpg"
  alt="Es una imagen de un perrito"
  />
  <figcaption>Es una imagen de un perrito</figcaption>  
</figure>

---
### Etiqueta video 15/55

La etiqueta `video` se utiliza como bien dice su nombre para colocar videos dentro de ella. Esta etiqueta tiene varios atributos y también otra etiqueta que se puede usar dentro de ella.

Atributos de la etiqueta `video`:

- `src` sirve para darle la dirección del video al navegador. Si quetemos que el video empiece a correr desde un punto específico y se detenga en un punto específico podemos utilizar el símbolo de número **#**, luego `t=10,60` esto hará que el video empiece en el segundo 10 y se detenga en el segundo 60.

- `controls` sirve para añadirle botones al video y que se pueda reproducir, además este atributo no lleva nada dentro (no lleva ningún valor).

- `preload` con el valor `auto` sirve para que el video cargue más rápido, el video se empieza a renderizar cuando la página se empieza a crear en el navegador y el usuario no tenga que esperar tanto para poder reproducirlo. Este atributo no sirve para que se empiece a reproducir solo.

La etiqueta `<source>` se utiliza dentro de la etiqueta de video y sirve para reemplazar el atributo `src` esto sirve para cuando queremos asegurarnos de que el navegador va a correr el video, es decir que el navegador pueda correr la extensión de video que le pongamos. por ejemplo: .mp4 .mv4 etc, estas son extensiones de videos y puede ser que algún navegador no corra una pero si la otra.

```
<body>
    <main>
        <section>
            <video controls preload="auto">
                <source src="./claseVideoPrueba.m4v#t=2,4">
                <source src="./claseVideoPrueba.mp4#t=2,4">
            </video>
        </section>
    </main>
</body>
```

---
### Etiqueta form e input 16/55

```
<body>
  <form action="">
    <label for="nombre">
      <span>¿Cuál es tu nombre?</span>
      <input type="text" id="nombre" placeholder="Tu nombre">
    </label>
    <label for="Inicio-platzi">
      <span>¿Qué día comenzaste en Platzi?</span>
      <input type="date" id="Inicio-platzi">
    </label>
    <label for="horario">
      <span>¿En qué horario estudias?</span>
      <input type="time" id="horario">
    </label>
  </form>
</body>
```

**HTML [Input Types](https://www.w3schools.com/html/html_form_input_types.asp)**

Here are the different input types you can use in HTML:

```
<input type="button">
<input type="checkbox">
<input type="color">
<input type="date">
<input type="datetime-local">
<input type="email">
<input type="file">
<input type="hidden">
<input type="image">
<input type="month">
<input type="number">
<input type="password">
<input type="radio">
<input type="range">
<input type="reset">
<input type="search">
<input type="submit">
<input type="tel">
<input type="text">
<input type="time">
<input type="url">
<input type="week">
```

---
### Calendar 17/55

[Input documentación y resumen](https://developer.mozilla.org/es/docs/Web/HTML/Element/input)

En ***vs code*** con windows se puede comentar un gran bloque de texto seleccionandolo y luego con las teclas `Ctrl+k + Ctrl+c`

El atributo de submit en input sirve para enviar la información de un formulario, incluso agrega el botón de enviar en el navegador.
`<input type"submit">`

```
<form action="">
  <label for="hora">
    <span>Hora</span>
    <input type="time" id="hora" name="hora">
  </label>
  <label for="dia">
    <span>Día</span>
    <input type="date" id="dia" name="dia">
  </label>
  <label for="semana">
    <span>Semana</span>
    <input type="week" id="semana" name="semana">
  </label>
  <label for="mes">
    <span>Mes</span>
    <input type="month" id="mes" name="mes">
  </label>
  <input type="submit">
</form>
```

<form action="">
  <label for="hora">
    <span>Hora</span>
    <input type="time" id="hora" name="hora">
  </label>
  <label for="dia">
    <span>Día</span>
    <input type="date" id="dia" name="dia">
  </label>
  <label for="semana">
    <span>Semana</span>
    <input type="week" id="semana" name="semana">
  </label>
  <label for="mes">
    <span>Mes</span>
    <input type="month" id="mes" name="mes">
  </label>
  <input type="submit">
</form>

```
<form action="">
  <label for="calendario">
    <span>Calendario</span>
    <input type="datetime-local" id="calendario" name="calendario">
  </label>
  <input type="submit">
</form>
```

<form action="">
  <label for="calendario">
    <span>Calendario</span>
    <input type="datetime-local" id="calendario" name="calendario">
  </label>
  <input type="submit">
</form>

---
### Autocomplete y require 18/55

`autocomplete` es un atributo que nos auto-completa las casillas siempre y cuando el navegador ya tenga esa información.

`required` es un atributo que no nos deja enviar el formulario hasta haber completado las casillas que tengan este atributo.

```
<body>
   <main>
    <form action="">
        <label for="nombre">
            <span>¿Cuál es tu nombre?</span>
            <input type="text" name="nombre" id="nombre" autocomplete="name" required/>
        </label>
        <label for="correo">
            <span>¿Cuál es tu correo?</span>
            <input type="email" name="correo" id="correo" autocomplete="email" required/>
        </label>
        <label for="pais">
            <span>¿En qué país vives?</span>
            <input type="text" name="pais" id="pais" autocomplete="country" required/>
        </label>
        <label for="cp">
            <span>¿Cuál es tu código postal?</span>
            <input type="text" name="cp" id="cp" autocomplete="postal-code" required/>
        </label>
        <input type="submit" />
    </form>
   </main>
</body>
```

<form action="">
  <label for="nombre">
    <span>¿Cuál es tu nombre?</span>
    <input type="text" name="nombre" id="nombre" autocomplete="name" required/>
  </label>
  <label for="correo">
    <span>¿Cuál es tu correo?</span>
    <input type="email" name="correo" id="correo" autocomplete="email" required/>
  </label>
  <label for="pais">
    <span>¿En qué país vives?</span>
    <input type="text" name="pais" id="pais" autocomplete="country" required/>
  </label>
  <label for="cp">
    <span>¿Cuál es tu código postal?</span>
    <input type="text" name="cp" id="cp" autocomplete="postal-code" required/>
  </label>
  <input type="submit" />
</form>

---
### Select 19/55

```
<body>
  <main>
    <select name="cursos" id="">
      <option value="JavaScript">JavaScript</option>
      <option value="HTML5">HTML5</option>
      <option value="CSS3">CSS3</option>
      <option value="">Web Standards</option>
    </select>
  </main>
</body>
```
<select name="cursos" id="">
  <option value="JavaScript">JavaScript</option>
  <option value="HTML5">HTML5</option>
  <option value="CSS3">CSS3</option>
  <option value="">Web Standards</option>
</select>

Se puede hacer un formulario que tenga una lista con cosas para seleccionar con esta etiqueta, pero la mejor manera de utilizarlo no es como se muestra arriba porque en un celular o incluso en una computadora si hay demasiadas opciones puede ser incomodo de seleccionar entre tantas opciones. La mejor manera de hacerlo es como sigue:

```
<body>
  <main>
    <input list="cursos">
    <datalist id="cursos">
      <option value="JavaScript"></option>
      <option value="HTML5"></option>
      <option value="CSS3"></option>
      <option value="Web Standards"></option>
    </datalist>
  </main>
</body>
```

Utilizando la etiqueta `<input list="cursos">` con el atributo list se puede hacer una lista.

<input list="cursos">
  <datalist id="cursos">
  <option value="JavaScript"></option>
  <option value="HTML5"></option>
  <option value="CSS3"></option>
  <option value="Web Standards"></option>
</datalist>

---
### Input type submit vs. Button tag 20/55

`input` para formularios.
`<button>` para cualquier otro tipo de boton que necesite en mi proyecto.

```
<input type="submit" value="Nombre" />

<button type="submit">Que color te gusta?</button>
```

<input type="submit" value="Nombre" />
Con el atributo `value` se puede escribir el texto que tendrá dentro el botón de input.

<button type="submit">Que color te gusta?</button>

---
### ¿Qué es CSS? 21/55

CSS es la herramienta para embellecer nuestro HTML.

<figure>
  <img 
  src="https://i0.wp.com/www.silocreativo.com/wp-content/uploads/2018/07/CSS3-modulos.png?resize=602%2C600&quality=100&strip=all&ssl=1"
  alt="CSS"/>
  <figcaption>Funcionalidades de CSS1, 2 y 3.</figcaption>
</figure>

---
### ¿Cómo utilizamos CSS?: por etiqueta, selector, class y por ID 22/55

`<link>` es una etiqueta que se puede utilizar para enlazar una hoja de estilos de CSS con mi html y es la mejor práctica.

`<style>` es una etiqueta que sirve para agregar CSS dentro del html, no es la mejor práctica, pero se puede usar si son pocas líneas.

`link` y `style` se utilizan dentro del head.

Otra forma de agregar CSS dentro de mi html es en el `<body>` utilizando la etiqueta `<p>` y luego dentro utilizando el atributo `style` en la etiqueta `<p>`.

`<p style="color: red;">Soy un texto</p>` esto se llama estilo embebido. Esta práctica tampoco es la mejor, no es bueno agregarle estilos a una etiqueta porque esto puede reescribir los estilos que tengamos en nuestro archivo CSS.

```
<style>
        p {
            color: blue;
        }
    </style>
```

#### Cómo utilizar CSS en la hoja de estilos?

Hay diferentes formas para utilizar CSS y las iremos enumerando.

1. Escribiendo la etiqueta a la cual queremos cambiarle el estilo.

```
p {
    color: blue;
    font-size: 40px;
}
```
En este caso le dimos estilo a la etiqueta `<p>`.

2. Utilizando el atributo `class` en el html, luego llamamos la clase que creamos en html al CSS.

```
En el archivo de html:
<p class="parrafo">Soy un texto</p>

Luego en el archivo de CSS:
.parrafo {
    color: red;
}
```

3. Utilizando el atributo `id` en el html, luego llamamos el id que creamos en html al CSS.

```
En el archivo de html:
<p id="texto">Soy otro texto</p>

Luego en el archivo de CSS:
#texto {
    color: yellow;
    font-size: 24px;
}
```

Es importante recordar que ID y class no se tratan de la misma manera, son diferentes.

---
### Pseudo clases y pseudo elementos 23/55

**Diferencias**

*Pseudo Clase*: Define el estilo de **un estado** especial de un elemento.

*Pseudo Elemento*: Define el estilo de **una parte** específica de un elemento.

[Standar para nombrar clases en CSS: BEM](https://en.bem.info/methodology/faq/#why-bem)

[Pseudo Clases](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-classes)

[Pseudo Elementos](https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-elements)

Barra de navegación creada con html.

```html
<header>
        <nav>
            <ul class="main-nav">
                <li class="main-nav__item"><a href="">Home</a></li>
                <li class="main-nav__item"><a href="">Cursos</a></li>
                <li class="main-nav__item"><a href="">Instructores</a></li>
                <li class="main-nav__item"><a href="">Blog</a></li>
            </ul>
        </nav>
</header>
```

Estilos de la barra de navegación utilizando CSS.

```css
.main-nav {
    margin-top: 10px;
    list-style: none;
    padding-left: 0px;
    background-color: #13a4a4;
    text-align: center;
}

.main-nav__item {
    display: inline-block;
}

.main-nav__item a {
    color: white;
    padding: 5px;
    border-radius: 2px;
    text-decoration: none;
}

/* Pseudo clase hover se llama con : */
.main-nav__item a:hover {
    color: blue;
}

.main-nav__item a:active {
    color: red;
}

/* Pseudo elemento after se llama con :: */
.main-nav__item a::after {
    content: " | ";
}
```

---
### Anatomía de una regla de CSS 24/55

<figure>
  <img src="https://lh3.googleusercontent.com/fife/ALs6j_HV61R2hCeglUeTjPHMg9Ez6wjJO9wYm7Goedt0xJwIcXhCJx6Y1XBr1Xn7l147O3oXN8NNVF47uGWTNK31W0gpDweBdoM4F01K8sSI5Wn9lWm4eijlGKOCE6qMjlilBT3VsG97a0or-V6nslLuoIrIzElX1UlGRxTvY1R7QiQ6KxuWBB27UI2V88lyqZRI5EFttZcHbeQzb4S4OAfuV-o5-H-00KmHn8EVTuORTFiGh_xDZ_mIjDfADCTrjubqeu28nZ7Ka0zypBgaqYWpB_s2jnYXQa4cxHhQVrPht1STQtIvJOBwJ4ysFkeC9LeM2C3WXVZHqVFcgfig5gRB1h1vssovtKeM9PmV9FqHiaRrn77ev1u4UEniOXeeeDfWaDiAugvr7R2hjSJvn2pAwGcLHUiFK0fXuo0c31bDFLiRC9OVXuOqYelcTj4WqLCoBqAO9RFaoeuZzgG4XAIgrpQU7Ws8g3M2m-qgSNjOwLmRXYsi9eVgXHreWQr1P_iYQ50zJxDck_V-hKjMF5HDUS2C9E1XVzVJKOdlUKGppdvTy7kXecSwyW5PNMv9VSJwEmhjFeYI0LtKpYGW9oChdkjsK40iLuOm_D92plPPUzlKdgPPy7vHHfnYpa7lkQ6aG656ZUuyZzLFXJ1XTXHzEADLMJMuuUQ-X-tt4HVwr2qmtaeftOPqYusOsic0bv_dHJmnAfDPRN0vSdhT7shc3dxwNYxn4WKfghlXggmqISJckhaXgh4d0XgVS-dbmR7nYNVd2-Tgzo1fiTkN2fDSEkWQfJXrbkOSAYGbUDxiWd6xH7T6AY9vrWpwdz5IuERwiHtE0LpbcCamyEJfkYETHie4Tc3vfbe9T-AtSyvO6jsfmq7GgryjxmG_MgQxa8J-Cid8PtIakWjjkcOIeAdVatC1EKJ3JikX8yJMZPnI-xPDlSbQbza36X0PyhCYUbNg7GqYRpewWXUatpIBi83J9OeFU4GpHWLbdVhgiv5t3Zw44rlLDpILVDfUJisQ7YOIrhKIjmZIKukDCMROo809KTNNqN3eZQM4FmfETU6CJbDzLuPJCpl_ltSwstUhzgjfsiEXriSInVEZVSzBjcpC0HDeL_G_0lBMa_1JxXHUDYuGtSL-hy2QcYorngvqdLPvVdJEmCRXoRx4a6Sr4IQCls1kYc00YQTAz3Uchc9RWZoRDXFtueT9D95HQr-bmOMlw5QwHg29VMO64dBeXmTZ7KG4cOUr8WbQNeQde9zzQWT46xZeraBK3LcNUKSghCnKW_I00qC-y6INyzkNxWkT0yMxVcgEslmEbr2U_UI9DcrLEkuYPTg7xbu-_wyP2ERvFKUlMudppU5k5c6tuVZbUl2lnOtr-HBe9pMfDm2De2lqrzxJ1jvHVOd2DOaVl0vFPZ4WC6I8p9kKordFNotB2-eb2TayMTOyKt51_cPiz9xU9PllErceR6vSZHKdibYKQsf4Z7s1JLvM5gVPjx5-afxUPziAZ7DWzeB5eoI5fWyzpPt2rqRGrDFjn7OqllAahHtjfyxOw0yJnlTkAWlKqgsNFJH7ZFBHs6t0ngVZ0QMv2ozN-58UwzaJiPWl4p4p7PdZawY7ix9bryca9292Ig=w1920-h945" 
  alt="Regla CSS" />
  <figcaption>Sintaxis o Regla de CSS (Imagen en google drive)</figcaption>
</figure>

---
### Modelo de caja 25/55

<figure>
  <img src="https://lh3.googleusercontent.com/fife/ALs6j_Hws7YG0ZHqvOmWqWT-wCyBA4unCiqnKN7haaWr4PnVJt-UPC4eLzGS8SeZVh_wNnPFTbo2isO7yNOPbUBfLuwUDlzVK--D7ErD8HoNZjVnUEP5-UWN2tguUceSUmz6motYUOYK5RV21uGo2a9rpRxkAIqxykzcc5WCcE1XqTLHgiVzvQ2SBTLmTQUAiCa3mTqX0_jDetLEUjsllVIwYG0x_56fVS8Ou1ByWxgzvIW1Dd24xvQUOiE4X-pACVlcpVXjEzkKjW3wSRhOD4u_IG4KGD2dAVPexpIGl9EAFrh7czxsic8QTH8HjFXH7UBa8DvCsYKxeO-s5JqPQTChmN1EvC7UhutQmdXaN_hk18ZtIdXeMUnzslz4ZbytDUpa4sIbzn1QCofO-GdDSxBirFT2oS17YXB8V6q01vnHfrESF0resGdC1hz_wtKxREy_qITSaiXnMz7FI1pCQDFaVX6fUAMc3oGur7_97qRUfmEAHeys1knJzfy1wRXKE5OsewqaPf4e1us6_uslEmGosJUI3-TzY7ystSOV_JoqahweeVrdpywaZ-xRpxy3kjoJrKiuz_6ZqrHHiDZh06X2hw4_nF2kb5B4zu8_izqaTdDAyruu9jyDZZ0FG5ByUMk7G3GQL9jpkR-9adYxLkyUm0d2uglTcWCRzjdZYW3TTskmPFMzzQVzm1TUBJYSlyfC29y2CFGuOiUBbrSKDeepWgMzaBhxcNg5NMPNK5CAM2YeseuBCXjGzu5kEaDjfL9sBjlrFYEyPT6yP2Uy4fh4j3GXXgkLG0Tw_CUz7Ihub1hpIpbxb2qc60JVBcF9AZT9w3_fCYh6MmnvkVt03ESMWW22rPIRtYNh-3Rqn1WPzB-ngLq_fPq4mBcMhSMtok-vnVfLz0chthl7CCNHdGx5tkpYnpAJxSg9JAwM0dX_2c1tVzhiksmwICDL3AV0oG5LvYYSStdKciYoL0PctesoNFZO_Fc8xW6PPqw8zSRPWvpiGg0c1-xHKP2xxNoKoqpu2nIZ7_VzI640BM67HSaKsHwD3oYfy_oDJvJWmCiiGYIHI9LHG4xzhnEsbxwqeZscB2WCPRYlQqu-X4rXSYQMimesyTk06PHyuFTeN8-v1nGWcaZy3EiLoehbmYHnBtNuAWbR-MZU-uQGzizZR_ra032nyqlfDnBBO_wlI-MZFExMdy_dUMGO8yhA8NRbnEI33iDjfYZqtMrmzRMcQe-N4PQimPoH5-8eb3a1udtunKCrvFnY_QgId60yHZEeTKQJ7EGSn5xgngRPIUA4hfb4DeNw5Z8ADYMB2xsMbYUJCg4bpnrsgpAd8hMAFk1JTphQSLJDITXQTNbNcl9dHUE8_UV1MUlFVZip7H6aGHFN3yoqNoaDE2aS8n2nO9WP5QvHYXSJa2rh8BtpcbH9q_5l_JSG3Q2K-qypcMQ6EpL25RhImC-xgtoC4HJwnWesa6UFozoiaIajaiEM5SP6KE_H0wrazWGxV2ZGoNzt65JyQoWUd1F_FIkcqUO9zV7F9bcPvn-2Up43Ffa9KAcwq4PzqbQJ8ypoNfp6bPReZKP6Mt_57h2AwWXtBFBAZfhR_Ru3I3aCyzDPbo73lG8F6gU=w1920-h945"
  alt="Modelo Caja CSS" />
  <figcaption>Modelo de Caja en CSS</figcaption>
</figure>

<figure>
  <img src="https://lh3.googleusercontent.com/fife/ALs6j_F5YDoJbgZalPUB9ChFPQvOjGyCWmZzGVHCLIkATt7NbfzmyK_sz3AwcOFAU7qk-j9KzHdgwH_CRlhahDDYqNJrhE8iYxBAAuERlhwdtHcMuXe9XMKTu4mXXcABobBM-nCaM36m0VK7EPX7VRojwr5yGRgBydPAyL_7y-6VbD0EfqYK4fPw9XlO9chNhsXT0bSlEo5ATh6UKxbWO-6y44ny6iL4I0KoZ172jnb08amMrQd7A80CzviPqhCxJcsgNBR5tHuR-BI3Bm6dM74al72_mbeKNUGD6GfjBa242wbSbKXQxEET5RiYxKJ1aP7A3YDviMINgN7iy-veNK14T6ekaEQ-PrSrppBmXDWm0Wgu2VrVWOcqdYQXtM7ccAhuk3rcsUimCyyATgrvfwS7SANz6XBZ70qHBTwaIsjVAtYYQPT0-7W3KCVdtYsO487jj_eIOmPuXXgqcayg9v6v_7TuPaRdMMj7qzqnBMOrxmAWxK3Md-A6bh-r4QoWooyoGRbrH_SfxOhyBIBkMAzwJ_DyEyRwlpDiURinlQKDDg78QFF8Sa4V8bqbR0JNhMmYZSU6USHAdkqCz4GhKsqwcYJrkLD0YFmFKkclmJaABi3pA3xiG1Q6hYinviXVO_mbTuGEb0qMBOWO_iSoRpQE3rRbN16YdMfsNtpXGQjYPIMriBl17DPdVElvSD-cTVZeg_nCc4mE1zp013X5eYUfZPJ1Al7KszQ20n5AL5_WvNpvCFJzgOMC6f7VH_CwnCQXB6lXNQ1_nQEs_HL2kHcY5Fe2imCU2yBsIyeE95VnLOQT2xof3cVO1dI3ZLcZdnZnbn6n0t4wCN0ywzcQBRfVQFd0Vx7C5IjgnquMBbUkVnir7CApIW4bWcokcTJf2xfYhl_GQdarFVGfMXzuW2GzzATlvtMwIYIFO8kZxSqi7jrh2rAw82f4zSu3nKC79XwJZPJk3w5giOXD_HpH6N3H3-cawWa3xygwnI-SVCFjHoNY3ES4E-J83I3gfioj6PQskzT4skSuA-pNbm3zrhpcNtighCX3qOG73nmaqEOn5-Qm_VqBJjXpR2MsApwujTl8seF21LalL_H97a-u7Z-WmYkqGCJCPTlewQzayAon8XxyWsHaMkP_sygv2Si8jJOxNqUB3VRaPA6mB6SQjHbslGLzr-dwv_TGC_eZ43cDkmhrlufDZNjY9EVInp-IoLETcYPnvdvXtg_pcnbPV6r_RYnuCQmghMnL3mxK7chQRLxR942h9muU9Kno1_AIa_9OxgKqZlnkYWykjrNjiXKk-xX5OKuEV62Vbu-3oSplup9IjGA00pFxoelsCkPjcQEvZhfQWEXfqKclkWHrzyHiFBg6sWJHwqU82-fDaoRWnvRUs54jWHWPs1AspAqRNZ_oO2kq8PMXcVk0FL3b5kUdRpWuKqL0sZ8-XRelY2XNgauMn04l_jbK7pbh4mTVjASH8YukmC2UIG34PcSPV6H2hgKQW0eTKJ3nTahdfn63PrUKB0_JIZV0k-qPza_70fsiugsAhOnaRtZNdXbWO1AsVg0k-j0judczWWgp27AHzrYI5jkfDRs-vOnG0bSeTHD_cm86aguS2EzU4S8BT-c=w1920-h945"
  alt="Modelo Desglosado">
  <figcaption>Modelo de Caja Desglosado</figcaption>
</figure>

Selector universal es el `*` (wild card)
```css
* {
    box-sizing: border-box;
    padding: 0%;
    margin: 0%;
}
```
Estas líneas son para limpiar todas las etiquetas y que no tengan esos estilos con los que vienen por defecto. Normalmente van al inicio del archivo css.

El **box-sizing** se utiliza para que se recalcule el tamaño del content en el *modelo de caja* de css, toma en cuenta el *padding* y el *border* pero **NO** el *margin*.

[box-sizing](https://developer.mozilla.org/es/docs/Web/CSS/box-sizing)

---
### Herencia 26/55

La herencia es el codigo CSS que se le pasará de un padre a un hijo.

```css
html {
    font-size: 75%;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}

h1 {
    font-size: inherit;
}
```

**inherit**: se utiliza para heredar del padre más cercano que cumpla con la condición, en este la condición es que el padre tenga un font-size y lo hereda de *html*.