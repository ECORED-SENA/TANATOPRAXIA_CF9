<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 
          i.fas.fa-info
      h1 Introducción
     
      
    .row.justify-content-end.bannerIntro--bg.mb-5            
      .col-lg-8
        .crd--banner
          p.mb-0 Apreciado aprendiz, la adecuación de un cuerpo sin vida para su traslado final implica el cumplimiento de protocolos de tanatopraxia y de la normatividad vigente, que conlleven a la prestación de un servicio según los requerimientos de los deudos. En este sentido, el presente ambiente de aprendizaje surge ante la necesidad de que desarrolle competencias para la verificación del proceso de tanatopraxia y tanatoestética de acuerdo con los protocolos establecidos. Por ello, se invita a  que revise el siguiente recurso de aprendizaje.     
        
    
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
        
      
    
   

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
