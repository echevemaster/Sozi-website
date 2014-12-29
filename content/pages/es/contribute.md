Title: Contribuir
Slug: 50-contribute
Lang: es
Author: Guillaume Savaton, Eduardo Echeverria
Translation: true

Traducir el sitio web a su lengua materna
----------------------------------------------

El sitio web de Sozi es un sitio estatico generado con [Pelican](http://blog.getpelican.com/).
No proporciona un editor en línea donde se puede editar, previsualizar y publicar sus contribuciones.

Los archivos de código fuente del sitio web son archivos de texto que usan la sintáxis [Markdown](http://daringfireball.net/projects/markdown/syntax)
Estos archivos están alojaos en el [repositorio Sozi-website en GitHub](https://github.com/senshu/Sozi-website), en el directorio
[content/](https://github.com/senshu/Sozi-website/tree/master/content).
El directorio  [content/pages/](https://github.com/senshu/Sozi-website/tree/master/content/pages) contiene la documentación de Sozi.
Esta dividido están divididos en subdirectorios por cada idioma (`en` para inglés, `fr` para Francés, etc)
los cuales contienen archivos Markdown.

Para empezar a traducir, recomendamos seguir los siguientes pasos:

1. [Forkea el repositorio](https://github.com/senshu/Sozi-website/fork).
2. Añada un subdirectorio para su idioma en  `content/pages/`, si no existe todavía.
3. Si ud. quiere traducir una página, busque la versión original en ingles en el directorio `en` y cree un nuevo archivo con el mismo nombre en su directorio de idioma correspondiente.
4. Edite el nuevo archivo.
5. Opcionalmente, puede utilizar Pelican para generar su propia copia dle sitio y previsualizar sus modificaciones.
6. Cuando este satisfecho con el resultado, haga commit y push de sus cambios en su repositorio de github y envie un pull request al repositorio oficial de Sozi.

La cabecera de un archivo Markdown traducido debe contener los siguientes campos:

* `Title`: el titulo de la página original, traducido a tu idioma.
* `Author`: lista separada por comas de los autores originales y traductores.
* `Slug`: el mismo del archivo original.
* `Lang`: el código de idioma de la traducción.
* `Translation`: se debe establecer en `true`.
