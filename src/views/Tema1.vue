<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 ¿Por qué es necesario probar los juegos?

    .row.justify-content-center.align-items-center
      .col-2
        figure
          img(src='@/assets/curso/temas/tema1/img1.png', alt="alt")      
      .col-10
        p Las empresas de desarrollo de juegos deben invertir lo suficiente en las pruebas de los videojuegos para garantizar que el producto final no tenga errores o bugs. Eso haría decaer la experiencia del jugador y la parte central de los juegos es la experiencia del consumidor. Con una buena experiencia de usuario, un juego prosperará. Hay millones de juegos en la App Store y la Play Store, pero ser un ganador entre esta dura competencia requiere mucha paciencia y trabajo. 

        p Con tantos juegos llegando al mercado diariamente, hay que ser diferente para destacar y dejar huella. Los niveles complejos no son suficientes para que los usuarios se enganchen a un juego y lo recomienden a sus amigos, ya que si el juego no funciona como los usuarios esperan, no tardarán en desinstalarlo y pasarse a otro.

    separador
    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1  Tipos de técnicas de pruebas de juegos

    .row.justify-content-center.align-items-center
      .col-1
        figure
          img(src='@/assets/curso/temas/tema1/img2.png', alt="alt")      
      .col-11
        p Los encargados de las pruebas de control de calidad en un estudio de videojuegos (QA, Quality Assurance) buscan los problemas y los puntos débiles que se pueden pulir antes de lanzar el producto al público, además, deben asegurarse, a través de diversas técnicas, que aspectos como la conectividad emocional con el juego o el nivel de diversión estén en óptimas condiciones.

    p.mt-3
      A continuación, detallamos algunas de las técnicas más comunes utilizadas por los estudios de videojuegos y los QA testers especialistas en pruebas de control de calidad de juegos:

    .tarjeta.tarjeta--azul.p-4.tema1-bg1
      SlyderA(tipo="b").p-5
        .row
          .col-md-6.mb-4.mb-md-0
            h4 Pruebas de Funcionalidad
            p La función de esta técnica de pruebas de juegos es comprobar si el videojuego funciona de acuerdo con las especificaciones. Algunos de los problemas que sigue la técnica de pruebas de funcionalidad son los gráficos genéricos, la interfaz, la estabilidad o los problemas mecánicos. Además, con esta técnica se pueden resolver errores como el freezing, el crashing o los bloqueos de progresión.

            p Los testers del juego están atentos a cualquier fallo gráfico en la interfaz, como gráficos ausentes, colores faltantes, problemas de ubicación o problemas de animación y recortes. Después de identificar todos los fallos y errores, los testers del juego hacen una lista y los envían a los desarrolladores del juego para que los arreglen. Una vez que los desarrolladores resuelven los problemas, envían el juego al equipo de control de calidad para que lo vuelvan a probar.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img3.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h4 Pruebas Combinatorias
            p Con esta técnica de pruebas de juegos, se puede comprobar inicialmente cuántas pruebas necesita el juego. La técnica de pruebas combinatorias analiza y escudriña todas las salidas y entradas del juego para que pueda obtener una imagen clara sobre las distintas combinaciones y resultados concebibles. Este hallazgo tiene importantes implicaciones para las pruebas, ya que sugiere que probar combinaciones de parámetros puede proporcionar una detección de fallos muy eficaz.

          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img4.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h4 Pruebas Ad Hoc
            p Este método no es algo formal, sino que, por el contrario, todos los procedimientos se realizan de forma aleatoria. Esta técnica de pruebas de juego también se denomina “adivinación de errores” y consiste en detectar los fallos mediante un enfoque aleatorio. Por lo tanto, no es necesaria ninguna documentación especial, como documentos de requisitos, planes de pruebas, casos de prueba, ni una planificación adecuada de las pruebas en cuanto a su calendario y orden de realización.

            p Dado que las pruebas ad hoc son más bien una técnica de prueba “salvaje” que no tiene que estar estructurada, la recomendación general es que se realicen después de la ejecución del conjunto de pruebas correspondiente. Otro punto de vista es que se puede realizar cuando no se pueden realizar pruebas detalladas por falta de tiempo.
            
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img5.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h4 Pruebas de Compatibilidad
            p Esta técnica de prueba de juegos te ayuda a validar si la interfaz de usuario es compatible con todos los tamaños de pantalla en los que se puede jugar. Cada dispositivo es único y puede presentar diferentes problemas, como el uso del hardware, los detalles gráficos, el tamaño de la pantalla o las aplicaciones de fondo. 

            p Tras la verificación, el videojuego debe cumplir los requisitos esenciales del software, el hardware y los gráficos. Realizar las pruebas de compatibilidad en dispositivos físicos es la mejor manera de determinar el rendimiento con precisión y conocer la experiencia del usuario final.
            
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img6.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h4 Pruebas de Cleanroom
            p La técnica de pruebas de cleanroom válida y mejora el rendimiento de la consistencia y la fiabilidad del software de juegos. Mediante el uso de las pruebas de cleanroom, se puede identificar la causa principal detrás de los bugs y pequeños errores. 

            p El plan es que los testers de juegos creen pruebas que jueguen al juego igual que los jugadores. Lo que significa que les resultará más fácil averiguar qué hacen los jugadores.
            
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img7.png', alt='Texto que describa la imagen')

        .row
          .col-md-6.mb-4.mb-md-0
            h4 Pruebas de Regresión
            p El propósito de esta técnica de prueba del juego es comprobar de nuevo si las funciones del juego operan de forma óptima, lo que ayuda a controlar la calidad que es tan importante para la experiencia de los jugadores. En la práctica, los testers de juegos vuelven a comprobar el juego y comparan los resultados actuales con los obtenidos en las pruebas. Quieren ver si se han producido nuevos errores debido a los cambios y ver si hay algún fallo antiguo.
            
          .col-md-6
            figure
              img(src='@/assets/curso/temas/tema1/img8.png', alt='Texto que describa la imagen')


    separador
    #t_1_2.titulo-segundo.color-acento-contenido
      h2 1.2  Métodos de prueba de juegos

    p Aquí es donde entramos en uno de los puntos más relevantes y nos centramos en los diferentes tipos de metodologías de prueba de control de calidad de juegos disponibles.

    .row
      .col-lg-7
        .list.mb-3(data-aos="fade-down")
          .list__item
            .list__item__icon
              img(src='@/assets/curso/temas/tema1/icon1.svg', alt='')
          .list__txt
            h3.mb-0.tv.margin-icon Pruebas de funcionalidad del juego

    .row.mb-5
      p Las pruebas funcionales son una actividad que tiene como objetivo determinar si un juego funciona de acuerdo con las especificaciones e identificar cualquier error o problema que pueda afectar negativamente la experiencia del jugador. Esto se aplica tanto a las pruebas de juegos móviles como a las de otras plataformas, incluidas PC, consolas, web y VR/AR. 

      p Podemos ordenar las pruebas en múltiples subtipos:

    .tarjeta.tarjeta--morada.p-4
      SlyderA(tipo="a")
        .row.justify-content-center.align-items-center.my-lg-4
          .col-6.col-lg-2.mb-5
            figure
              img(src='@/assets/curso/temas/tema1/img9.png', alt='Texto que describa la imagen')

          .col-md-9.mb-4.mb-md-0
            .tarjeta--blanca
              .tabla-a
                table
                  thead
                  tbody
                    tr.text-center
                      td #[b Subtipos]
                      td #[b Descripción]
                      td #[b Cuándo se necesita]

                  tbody
                    tr
                      td #[b Pruebas de juego de interoperabilidad]
                      td Se utiliza para probar cómo un juego interactúa con otras aplicaciones. Los probadores buscan cualquier problema de compatibilidad, incluida la inaccesibilidad de las funciones, el bajo rendimiento y los retrasos en la comunicación.
                      td Se utiliza principalmente para juegos multijugador y aquellos que hacen uso de funciones avanzadas del dispositivo (por ejemplo, enlace ascendente de Internet, Bluetooth, cámara, etc.).

        .row.justify-content-center.align-items-center.my-lg-4
          .col-6.col-lg-2.mb-5
            figure
              img(src='@/assets/curso/temas/tema1/img9.png', alt='Texto que describa la imagen')

          .col-md-9.mb-4.mb-md-0
            .tarjeta--blanca
              .tabla-a
                table
                  thead
                  tbody
                    tr.text-center
                      td #[b Subtipos]
                      td #[b Descripción]
                      td #[b Cuándo se necesita]

                  tbody
                    tr.text-center
                      td #[b Pruebas de juegos de regresión]
                      td Este ciclo se aplica después de las principales actualizaciones de código para asegurarse de que la actualización no haya afectado negativamente la funcionalidad existente (por ejemplo, rompiendo una función, agregando numerosos errores nuevos, etc.). El objetivo es asegurarse de que el código aún funcione.
                      td Esta es una práctica muy común tanto durante el desarrollo (cuando se crean nuevas compilaciones) como en el período posterior al lanzamiento, cuando se implementan el mantenimiento y las actualizaciones. Puede automatizar muchas de estas pruebas.


        .row.justify-content-center.align-items-center.my-lg-4
          .col-6.col-lg-2.mb-5
            figure
              img(src='@/assets/curso/temas/tema1/img9.png', alt='Texto que describa la imagen')

          .col-md-9.mb-4.mb-md-0
            .tarjeta--blanca
              .tabla-a
                table
                  thead
                  tbody
                    tr.text-center
                      td #[b Subtipos]
                      td #[b Descripción]
                      td #[b Cuándo se necesita]

                  tbody
                    tr
                      td #[b Pruebas de juegos de humo]
                      td La prueba de humo se trata de verificar la estabilidad después de una actualización de código. Sin embargo, tiende a ser una evaluación realmente simple, verificando cosas básicas como si el juego se inicia, si la interfaz de usuario sigue respondiendo. Puede ser realizado tanto por desarrolladores como por probadores.
                      td La prueba de humo tiende a realizarse justo antes de la prueba de regresión, por lo que podemos decir que es igual de común y esencial para todos los proyectos. Se considera una buena práctica para realizar todos los días del proyecto.

        .row.justify-content-center.align-items-center.my-lg-4
          .col-6.col-lg-2.mb-5
            figure
              img(src='@/assets/curso/temas/tema1/img9.png', alt='Texto que describa la imagen')

          .col-md-9.mb-4.mb-md-0
            .tarjeta--blanca
              .tabla-a
                table
                  thead
                  tbody
                    tr.text-center
                      td #[b Subtipos]
                      td #[b Descripción]
                      td #[b Cuándo se necesita]

                  tbody
                    tr
                      td #[b Pruebas de juego de localización]
                      td Este método tiene como objetivo garantizar que un juego sea totalmente utilizable y agradable para los jugadores de diferentes países y regiones. En primer lugar, todas las mismas características y funcionalidades deben ser accesibles en diferentes ubicaciones (a menos que se planifique lo contrario). En segundo lugar, el contenido debe adaptarse a los idiomas y culturas donde se presenta.
                      td Este tipo de prueba es vital si planeas lanzar tu juego en varios idiomas, o si planeas hacer que el contenido esté disponible en diferentes regiones. Por lo tanto, es preferible que los evaluadores tengan un amplio conocimiento de los idiomas/culturas asociados antes de comenzar a evaluar el software.

        .row.justify-content-center.align-items-center.my-lg-4
          .col-6.col-lg-2.mb-5
            figure
              img(src='@/assets/curso/temas/tema1/img9.png', alt='Texto que describa la imagen')

          .col-md-9.mb-4.mb-md-0
            .tarjeta--blanca
              .tabla-a
                table
                  thead
                  tbody
                    tr.text-center
                      td #[b Subtipos]
                      td #[b Descripción]
                      td #[b Cuándo se necesita]

                  tbody
                    tr
                      td #[b Pruebas de juego de control de acceso de seguridad]
                      td Una práctica muy importante que verifica si existen lagunas o puertas de enlace no autorizadas que puedan permitir que alguien acceda al backend del juego o a elementos/características que de otro modo estarían restringidas. Por ejemplo, algunos jugadores intentan piratear juegos para obtener recompensas o dinero gratis en el juego, hacerse invencibles, etc. y el control de acceso lo impide o al menos reduce la probabilidad.
                      td Aunque esta forma de prueba rara vez conduce a cambios que afecten la experiencia del usuario o que sean incluso perceptibles, se recomienda realizarla al menos una vez antes del lanzamiento y cada actualización posterior al lanzamiento. Puede ser realizado por ingenieros generales de control de calidad del juego o probadores de pluma (penetración) experimentados.

        .row.justify-content-center.align-items-center.my-lg-4
          .col-6.col-lg-2.mb-5
            figure
              img(src='@/assets/curso/temas/tema1/img9.png', alt='Texto que describa la imagen')

          .col-md-9.mb-4.mb-md-0
            .tarjeta--blanca
              .tabla-a
                table
                  thead
                  tbody
                    tr.text-center
                      td #[b Subtipos]
                      td #[b Descripción]
                      td #[b Cuándo se necesita]

                  tbody
                    tr
                      td #[b Pruebas de juego de aceptación del usuario]
                      td Esta es una de las últimas etapas de prueba antes de lanzar un juego en producción. A veces, se lleva a cabo como una prueba beta, atrayendo a jugadores fuera del equipo de desarrollo. Rara vez se encuentran grandes problemas, por lo que la atención se centra principalmente en pulir los errores menores restantes y realizar pequeñas mejoras en la experiencia del usuario.
                      td Al involucrar a probadores beta externos, puede obtener una nueva perspectiva sobre la experiencia del jugador y recopilar comentarios valiosos sobre posibles mejoras que el equipo de desarrollo no conocía o no prestó suficiente atención. Por ejemplo, las pruebas beta de juegos móviles pueden atraer a un grupo de edad con ideas y deseos únicos que su equipo de pruebas de adultos no tuvo en cuenta.







</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
