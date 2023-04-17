<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Cómo iniciar las pruebas o testing en un videojuego

    .row.justify-content-center.align-items-center
      .col-6.col-lg-2.mb-3
        figure
          img(src='@/assets/curso/temas/tema2/img1.png', alt="alt")      
      .col-lg-10
        p En teoría, cualquiera puede aprender a probar un juego, incluso si no está capacitado para ser un ingeniero de control de calidad. Sin embargo, tener éxito y eficacia en las pruebas es otra cuestión, y los proyectos a gran escala generalmente necesitan evaluadores calificados para tener éxito. Por lo tanto, puede considerar contratar a estos profesionales o delegar las pruebas a una empresa con amplia experiencia en el campo.
        p Cualquiera que sea la opción que elija, el proceso de prueba será más o menos el mismo. Entendemos que las docenas de tipos de pruebas que enumeramos son únicas y requieren software, metodología y conocimientos diferentes, pero las etapas de las pruebas suelen ser uniformes como se observa a continuación:

    .row.justify-content-center.my-5
      .col-lg-10
        PasosA.color-acento-contenido.my-5(tipo="n")
          .row
            .col-md-9.mb-4.mb-md-0
              h3 Planificación
              p Tienes que caminar antes de correr y las pruebas no son diferentes. En lugar de probar cuando surge la necesidad, puede hacer que el proceso sea más eficiente creando un plan integral con una lista de casos de prueba y cronología.
            .col-md-3
              figure
                img(src='@/assets/curso/temas/tema2/img2.png', alt='Texto que describa la imagen')

          .row
            .col-md-3.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/temas/tema2/img3.png', alt='Texto que describa la imagen')
            .col-md-9
              h3 Pruebas
              p No hay mucho que decir sobre esta etapa. Una prueba puede durar entre unos minutos y varios días. No es raro que se realicen varias pruebas simultáneamente.
              

          .row
            .col-md-9.mb-4.mb-md-0
              h3 Informes de errores y correcciones
              p Los ingenieros de control de calidad encuentran muchos tipos de errores en las pruebas de juegos y es su trabajo documentarlos todos. Los datos de la prueba y los errores/problemas identificados se empaquetan en un informe de errores y se envían a los desarrolladores para que los corrijan en una compilación futura.
          
            .col-md-3
              figure
                img(src='@/assets/curso/temas/tema2/img4.png', alt='Texto que describa la imagen')

          .row
            .col-md-9.mb-4.mb-md-0
              h3 Informes de errores y correcciones
              p Los ingenieros de control de calidad encuentran muchos tipos de errores en las pruebas de juegos y es su trabajo documentarlos todos. Los datos de la prueba y los errores/problemas identificados se empaquetan en un informe de errores y se envían a los desarrolladores para que los corrijan en una compilación futura.
          
            .col-md-3
              figure
                img(src='@/assets/curso/temas/tema2/img5.png', alt='Texto que describa la imagen')



</template>

<script>
export default {
  name: 'Tema2',
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
