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

    .row
      p Las pruebas funcionales son una actividad que tiene como objetivo determinar si un juego funciona de acuerdo con las especificaciones e identificar cualquier error o problema que pueda afectar negativamente la experiencia del jugador. Esto se aplica tanto a las pruebas de juegos móviles como a las de otras plataformas, incluidas PC, consolas, web y VR/AR. 

      p Podemos ordenar las pruebas en múltiples subtipos:


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
