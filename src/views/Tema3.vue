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
