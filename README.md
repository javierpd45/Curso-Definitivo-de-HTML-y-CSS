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