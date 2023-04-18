<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Utilizando el Framework Test Runner - Unit testing en unity

    .row.justify-content-center.mb-5
      .col-8.col-lg-3
        figure
          img(src='@/assets/curso/temas/tema3/img1.png', alt='Texto que describa la imagen')        

      .col-lg-9
        p Se ha decidido crear un solo epígrafe para las pruebas tanto unitarias como de integración dado que, por la naturaleza del propio programa, Unity y de los juegos como software desarrollado es casi imposible encontrar elementos aislados de código que funcionen sin depender de otros.
        p Es importante mencionar que en este apartado aparte de las pruebas realizadas también se han considerado como pruebas los logs generados durante el desarrollo del proyecto, así como las ejecuciones en el editor como parte de la integración porque al tratarse de un juego, los elementos debían coordinarse a la perfección para no obtener bugs indeseados.

      p De esta manera se subsanan errores que aparecían al producirse excepciones en el código. Para llevar a cabo estas pruebas se ha hecho uso de una funcionalidad implementada por Unity llamada Test Runner que permite su configuración y ejecución. 


    .row.justify-content-center.mb-5
      .col-lg-10
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-4
          .bloque-texto-g1__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/img2.png')})`}"
          )
          .bloque-texto-g1__texto.p-3
            p.mb-4 Algo que la mayoría de las veces solemos dejar completamente de lado a la hora de desarrollar nuevas features en nuestros juegos son, sin duda, los Unit Tests.
            p El Unity Test Runner hace uso de la #[b librería NUnit que es una librería de pruebas de software libre para lenguajes .Net.] El Test Runner permite ejecutar los test tanto en modo editor (edit mode) como en modo de juego (play mode). 

    .row.mb-5
      p Sin embargo, el uso de estas herramientas que proporciona el software de Unity 3D se deja casi siempre de lado ya sea por poco conocimiento sobre el uso de este framework, ya que este posee muchas bondades. De esta manera cabe resaltar que la implementación de estos test en nuestros proyectos siempre nos va a demandar un buen gasto de tiempo y esfuerzo extra que no siempre podemos o estamos dispuestos a perder, sumado a la falsa sensación de pérdida de tiempo por estar invirtiendo una parte importante de nuestro trabajo en desarrollar código que ni siquiera pertenece al producto final, puede que el hacer un repaso de algunos de sus pros y contras nos haga verlo de otro modo. Al respecto:

    .row.mb-5
      .col-lg-6
        .tarjeta-morada.p-4
          .row.justify-content-center
            .col-6.col-lg-3.mb-4
              figure
                img(src='@/assets/curso/temas/tema3/img3.svg', alt='Texto que describa la imagen').animacion-img-3

          h4.text-center.texto-blanco Ventajas 

          ul.lista-ul--color
            li
              i.fas.fa-plus.color-vineta1
              span.texto-blanco
                | Aplicar test en nuestro código nos da seguridad y confianza en el comportamiento esperado de las lógicas que implementamos.]
            li
              i.fas.fa-plus.color-vineta1
              span.texto-blanco
                | Algo muy importante es que sirve como documentación para nuevos desarrolladores que trabajen en tu código.
            li
              i.fas.fa-plus.color-vineta1
              span.texto-blanco
                | Nos obliga a implementar las cosas enfocándonos siempre a su testeo.
            li
              i.fas.fa-plus.color-vineta1
              span.texto-blanco
                | Nos ayuda a anticipar y localizar posibles bugs de manera más rápida y eficiente.
            li
              i.fas.fa-plus.color-vineta1
              span.texto-blanco
                | Nos convierte en mejores profesionales.



      .col-lg-6
        .tarjeta-azul.p-4
          .row.justify-content-center
            .col-6.col-lg-3.mb-4
              figure
                img(src='@/assets/curso/temas/tema3/img3.svg', alt='Texto que describa la imagen').animacion-img-3

            h4.text-center Desventajas 

          ul.lista-ul--color
            li
              i.fas.fa-times.color-vineta2
              | Inversión de tiempo extra de desarrollo (a veces puede llegar a ser demasiado).
            li
              i.fas.fa-times.color-vineta2
              | No siempre es fácil testear todo (por ejemplo, comportamientos de UI).
            li
              i.fas.fa-times.color-vineta2
              | No implementarlos de manera adecuada puede crearnos una falsa seguridad que puede ser peligrosa.










</template>

<script>
export default {
  name: 'Tema3',
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
