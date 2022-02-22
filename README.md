# Tienda de ropa - Proyecto Coderhouse de Jack Zorola

Este es el proyecto de ecommerce para el curso de frontend de Desarrollo Web de Coderhouse. 

## Tecnologias Utilizadas
HTML, CSS, SASS, SEO.

### Conceptos 
#### HTML
- Cada pagina tiene una estructura y comentarios. 
    - Usualmente iniciando con el menú en el tag <header>. 
    - En ocasiones una sección "hero" de contenido que se busca que el usuario vea en la inmediatez. Tal es el caso de camisetas.html e index.html.
    - Finalizando siempre con un <footer>.
- Adicional, se ha separado cada sección del html para que tenga sentido con las secciones que visualmente el usuario distinguiría como conceptualmente distintas. 
    - El carrito, del total
    - Las distintas categorias de productos
- Cada pagina tiene ligado sus estilos. 

#### CSS
- Se usaron estructuras de grids en cada pagina, estas a su ves quedarón centralizadas en [_estructura.scss](https://github.com/jackzorola10/tiendaropa-zorola-sass/blob/main/scss/_estructura.scss).
- Se utilizó flexbox para finalizar la estructura de multiples componentes. 
- @keyframes fueron utilizados para crear una animación en el hero del homepage. De momento se dejo con una transición muy rapida solo para mostrar la funcionalidad. [_heroHomepage.scss](https://github.com/jackzorola10/tiendaropa-zorola-sass/blob/main/scss/_heroHomepage.scss)
- @media queries estan aplicados a lo largo del proyecto para otorgar responsividad. 


#### SASS
- Se utilizó Sass para estructurar el proyecto y aprovechar las ventajas de esta tecnología. 
- Se utilizaron operadores de lenguaje de Sass en los colores, para establecer la paleta de colores y variaciones. [_colores.scss] (https://github.com/jackzorola10/tiendaropa-zorola-sass/blob/main/scss/_colores.scss)
- Se usarón nestings para agrupar el codigo de manera mas legible a lo largo de todo el proyecto. 
- Se puede encontrar ademas el [package.json](https://github.com/jackzorola10/tiendaropa-zorola-sass/blob/main/package.json) con la documentación necesaria.


#### SEO
- Cada pagina contiene titulos especificos al contenido.
- Cada pagina contiene meta descripciones y keywords enfocados al contenido de la pagina.
- El contenido de imagenes ha sido optimizado, reduciendo la resolución a un minimo optimo. Se utilizó: 
    - [Optimizilla](https://imagecompressor.com) 
    - [TinyPng] (https://tinypng.com)
    - [Photopea] (https://www.photopea.com)
- Se llevaron a cabo varios analisis en lighthouse donde se busco reparar los comentarios que hacia el reporte, esta es la calificación final que se logró obtener [Lighthouse] ().
- Se extrajo ademas un sitemap añadido en la ruta del proyecto [sitemap.xml](https://github.com/jackzorola10/tiendaropa-zorola-sass/blob/main/sitemap.xml).


### Paginas del proyecto
- [Homepage] (https://jackzorola10.github.io/tiendaropa-zorola-sass/)
    - [Camisetas] (https://jackzorola10.github.io/tiendaropa-zorola-sass/secciones/camisetas.html)
    - [Nosotros] (https://jackzorola10.github.io/tiendaropa-zorola-sass/secciones/nosotros.html)
    - [Contacto] (https://jackzorola10.github.io/tiendaropa-zorola-sass/secciones/contacto.html)
    - [Carrito] (https://jackzorola10.github.io/tiendaropa-zorola-sass/secciones/contacto.html)


