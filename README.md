# PreEntrega 3 - Curso desarrollo web de Coderhouse

## Información General

Esta entrega presenta el proyecto final web completamente maquetado para versiones de móvil, tableta y escritorio. Se ha desarrollado siguiendo la metodología mobile-first y se han empleado los siguientes breakpoints: 768px y 1200px.

El estilado se ha desarrollado completamente en SASS utilizando la sintaxis de SCSS. Se he intentado estructurar el estilado de forma que cada componente tenga su propia hoja de estilos.

Se ha buscado tener el mayor número de clases genéricas posibles para reducir al máximo el código repetido.

Se han empleado variables globales para los colores y elementos de la estructura general de la página.

En ningún momento se emplea Bootstrap en este proyecto.

En cuanto al módulo para la compilación de sass: he usado directamente sass en vez de node-sass. Previamente a este curso había trabajado con sass y me siento más cómodo a la hora de estructurar el código con el compilador de sass.

De igual modo, no he empleado @import para los diferentes módulos de sass. En su lugar he empleado @use y @forward ya que sass no recomienda el uso de @import hoy en día.

Se han buscado utilizar HTML semántico en la mayor medida posible. Todas las imágenes tienen alt. He incluido un favicon y las técnicas de meta tags description y keywords.

## Estructura de la página

Para plantear la estructura de la página he preferido emplear el sistema de grid propio de CSS (gridbox) así como flexbox para algunos componentes.

## Publicación de la web

Esta página web se ha publicado directamente en github pages: https://jsainzfc.github.io/PF-Sainz-de-la-Maza/
