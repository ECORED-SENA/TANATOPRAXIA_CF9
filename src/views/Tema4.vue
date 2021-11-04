<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5  

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Verificación y ajustes: embalsamamiento

    .row.justify-content-center.align-items-center.bg--gray
      .col-lg-4.position-relative.mb-4.mb-lg-0(data-aos="zoom-in") 
        figure
          img(src="@/assets/curso/tema_4/img_4_01.png", alt="alt").m-auto  
      .col-lg-8.position-relative       
        p.mb-0 En los procesos de calidad de cualquier organización es importante hacer un seguimiento detallado al antes, durante y después de la entrega de un beneficio y solución de una necesidad, obtenido por un cliente por un intercambio económico. Esta situación también se presenta en el servicio funerario cuando el deudo o cliente establece una comunicación con la empresa funeraria para dar atención a un requerimiento de adecuación de un cuerpo fallecido. El cadáver es custodiado por la empresa funeraria para el desarrollo de la tanatopraxia, esta se desarrolla en tres momentos: 

    .row.justify-content-center.bg--grayHalf.pt-5.mb-5
      .col-auto.mb-5(data-aos="flip-right") 
        .crd.crd--topLine.bg_topLine_01 
          figure.mb-4
            img(src="@/assets/curso/tema_3/img_3_04.svg", alt="alt",style="width:90px;").m-auto
          h4.text-center Desinfección
          p.text-center Desinfección del cuerpo e instrumentos para la eliminación de la mayoría de los agentes patógenos que pueden afectar la salud pública y obstaculizar la preservación química.   
          .hr_divider.m-auto
      .col-auto.mb-5(data-aos="flip-right") 
        .crd.crd--topLine.bg_topLine_02
          figure.mb-4
            img(src="@/assets/curso/tema_3/img_3_05.svg", alt="alt",style="width:90px;").m-auto
          h4.text-center Preservación química
          p.text-center Acondicionamiento del cuerpo sin vida para retrasar la descomposición por un tiempo determinado que permita la realización de los rituales.   
          .hr_divider.m-auto
      .col-auto.mb-5(data-aos="flip-right") 
        .crd.crd--topLine.bg_topLine_03
          figure.mb-4
            img(src="@/assets/curso/tema_3/img_3_06.svg", alt="alt",style="width:90px;").m-auto
          h4.text-center Tanatoestética
          p.text-center Acomodación de las posiciones y las facciones del fallecido, con el propósito de darle una apariencia natural que conlleve a generar una memoria en los deudos.   
          .hr_divider.m-auto

    .row.justify-content-center.align-items-center.mb-5        
      .col-lg-8.position-relative.mb-4.mb-lg-0       
        p.mb-0 Los anteriores momentos que se ejecutan en un cuerpo sin vida son inherentes a la naturaleza de la tanatopraxia, los cuales se ejecutan desde unos procedimientos dados en una orden de servicio, y son avalados por la normatividad vigente en el contexto colombiano. Cuando se han terminado estos procesos de adecuación del cadáver es necesario la verificación de las prácticas técnicas que han sucedido en el laboratorio, con la intención de ajustar alguna intervención hecha por el tanatopractor, según los requerimientos de los clientes y los protocolos de embalsamamiento. 
      .col-lg-4.position-relative.mb-4.mb-lg-0(data-aos="zoom-in")  
        figure
          img(src="@/assets/curso/tema_4/img_4_02.png", alt="alt").m-auto

    .row.justify-content-center.clr--bgGreenPale.mb-5
      .col-lg-8.position-relative.mb-4.mb-lg-0
        p.mb-4 Una vez realizada la tanatopraxia ingresa el director de servicio con la intención de verificar los procesos ejecutados y esperados por los deudos. Algunas acciones que este ejecuta dependen de las condiciones de la muerte de la persona. La revisión puede suceder es estos escenarios: 
        ol.lista-ol--cuadro.lista-ol--separador
          li 
            .lista-ol--cuadro__vineta
              span 1
            | Cuando la muerte ha sido sin ninguna anormalidad en la descomposición, el director de servicio valora condiciones y posición del cadáver en el cofre o ataúd.
          li 
            .lista-ol--cuadro__vineta
              span 2
            | Cuando el fallecido presenta una descomposición avanzada, el director de servicio debe verificar que el cofre se haya sellado herméticamente. Él inspecciona que el cofre esté bien externamente: limpio, sin rayones, sin hendiduras y completamente cerrado con una cinta
          li 
            .lista-ol--cuadro__vineta
              span 3
            | Cuando el cadáver ha sido adecuado por otros funcionarios externos a la empresa, el director de servicio revisa junto con los tanatopractores si el cuerpo cumple con las condiciones esperadas o de lo contrario, se hacen ajustes al cadáver. 
      .col-lg-4.position-relative(data-aos="zoom-in")
        figure
          img(src="@/assets/curso/tema_4/img_4_03.svg", alt="alt").m-auto.img--350

    p.mb-5 Con todo lo anterior, se hará una aproximación a los aspectos que se consideran en la verificación de la tanatopraxia. Las empresas funerarias compilan estos en un documento, que cuando pasa por las etapas del traslado existe una persona que verifica el proceso desarrollado. A continuación, se invita a identificar las características de cada uno para que las pueda aplicar en su contexto laboral. 

    .tarjeta.p-4.p-md-5.mb-5.corner_bg.bg--gray 
      .row.justify-content-around.align-items-center
        .col-8.col-sm-6.col-md-4.mb-4.mb-md-0(data-aos="zoom-in")
          img(src="@/assets/componentes/infografia.svg")

        .col-md.col-lg-6
          h3 Verificación y ajustes de la tanatopraxia
          p.mb-4 El embalsamamiento es un proceso que se ha practicado en diferentes culturas con el objetivo de postergar la descomposición de un cadáver a través de diferentes formas y métodos que han estado en historia del hombre. Este procedimiento puede considerándose una de las artes de mayor antigüedad practicada por los hombres.          
            br
            br
            |En la actualidad, el embalsamamiento se práctica a partir de unas acciones tradicionales,  normatividad vigente y protocolos institucionales que tratan de atender las necesidades de los deudos. Para conocer más sobre este tema consulte el siguiente recurso.
          
          a.boton.color-acento-botones(:href="obtenerLink('/downloads/Verificacion_Tanatopraxia.pdf')" target="_blank" type="application/pdf")
            span Descargar
            i.fas.fa-file-download

    .row.justify-content-start.bannerTema4--bg.mb-5            
      .col-lg-8
        .crd--banner
          p.mb-0 Para finalizar esta experiencia de aprendizaje es importante mencionar que #[strong la verificación del servicio funerario no solo se enfoca en los procedimientos dados en el laboratorio], sino que estos también #[strong.clr--green deben corroborarse desde el traslado inicial], cuando un funcionario atiende un requerimiento e inicia procesos administrativos y normativos para adecuar un cuerpo sin vida, y en la disposición final del cuerpo, ya sea por inhumación o cremación. #[strong.clr--red Recuerde que todo el proceso desarrollado en el servicio funerario debe asegurar la salud pública y la adecuación del cuerpo sin vida para las honras fúnebres.] 


    

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
