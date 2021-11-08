<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Tratamiento de datos en el sector funerario

    .bg--gray.mb-5
      .row.justify-content-center.align-items-center
        .col-lg-4.position-relative.mb-4.mb-lg-0(data-aos="zoom-in")    
          figure
            img(src="@/assets/curso/tema_3/img_3_01.png", alt="alt").m-auto  
        .col-lg-8.position-relative       
          p.mb-0 Durante el servicio funerario surgen diferentes procesos que están vinculados con el uso de información del cuerpo fallecido y los deudos. Todo ello conlleva a personalizar el traslado de un resto mortal; pero toda la información que surge tiene un tratamiento en la gestión de la información y protección de esta según la normatividad colombiana. #[strong Empiece por identificar cómo se puede poner en funcionamiento el sistema de información en una organización] para que ayude a generar valor en los procesos que desencadena una solicitud, para ello observe el siguiente recurso educativo.


    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/RFWax6M079k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)        

    .row.justify-content-center.align-items-center.bg--gray.mb-5
      .col-lg-5.mb-5.mb-lg-0(data-aos="zoom-in")  
        figure
          img(src="@/assets/curso/tema_3/img_3_02.png", alt="alt").m-auto
      .col-lg-7.onTop
        .bg--white.mb-4.neg--left
          p.mb-0 Retomando el video anterior, las empresas hoy en día tienen sistemas de información que ayudan a desarrollar sus procesos de forma más efectiva porque la disponibilidad de información puede estar en cualquier momento en la organización. #[strong Con el surgimiento de las Tecnologías de la Información y la Comunicación las empresas están haciendo transformaciones digitales], que cada vez ayudan a generar más valor a la empresa y a los clientes.
        p Por otra parte, el uso de la información en cualquier proceso de una empresa cuando unos clientes acceden a un servicio o producto está protegida por la normatividad vigente en Colombia. Esta reconoce y protege el derecho de las personas a conocer, rectificar y actualizar su información almacenada en base de datos o archivos que sean susceptibles de tratamiento por parte de entidades privadas o públicas. Algunas normativas que la legitiman son: #[strong.clr--green 1) Constitución Política de Colombia, en su Artículo 15, 2) Ley 1266 de 2008, en sus Artículos 2 y 4, 3) Ley 1581 de 2012 y 4) Decreto 1377 de 2013].
      .col-12.mt-4
        .row.justify-content-center.align-items-center          
          .col-lg-7.order-2.order-lg-1
            p En consonancia con lo anterior, se ha preguntado #[strong ¿qué es un dato personal?, ¿qué es eso de la protección de los datos?] A pesar de que todos los días se entrega información a terceros para que sea guardada en bases de datos, existen muchas personas que desconocen el derecho que tienen las instituciones que recolectan su información. Como proveedor de información tiene el derecho de conocer, actualizar, rectificar y eliminar los datos dados a una entidad pública o privada. En este sentido, cuando le solicita información a un deudo sobre la persona fallecida y otros, es importante comunicarles que sus datos serán tratados para los fines del procedimiento solicitado. 
          .col-lg-5.mb-5.mb-lg-0.order-1.oder-lg-2(data-aos="zoom-in") 
            figure
              img(src="@/assets/curso/tema_3/img_3_03.png", alt="alt").m-auto 

    p.mb-5 Para ayudarle a definir qué es un dato personal, #[strong.clr--green la Superintendencia de Industria y Comercio (s.f.) lo define como cualquier información que pueda ser relacionada con una persona. Existen tres tipos de datos personales:] 

    .row.justify-content-center.mb-5
      .col-auto.mb-5.mb-xl-0(data-aos="flip-right") 
        .crd.crd--topLine.bg_topLine_01 
          figure.mb-4
            img(src="@/assets/curso/tema_3/img_3_04.svg", alt="alt",style="width:90px;").m-auto
          h4.text-center Datos íntimos
          p.text-center Como principal característica pertenecen e interesan únicamente a la persona sobre la cual recae la información. Solo pueden ser obtenidos a partir del consentimiento del titular. 
          .hr_divider.m-auto
      .col-auto.mb-5.mb-xl-0(data-aos="flip-right") 
        .crd.crd--topLine.bg_topLine_02
          figure.mb-4
            img(src="@/assets/curso/tema_3/img_3_05.svg", alt="alt",style="width:90px;").m-auto
          h4.text-center Datos semiprivados
          p.text-center Estos datos le interesan al titular y a un grupo determinado de personas. Estos pueden consultar la información mediante una autorización.  
          .hr_divider.m-auto
      .col-auto.mb-5.mb-xl-0(data-aos="flip-right") 
        .crd.crd--topLine.bg_topLine_03
          figure.mb-4
            img(src="@/assets/curso/tema_3/img_3_06.svg", alt="alt",style="width:90px;").m-auto
          h4.text-center Datos públicos
          p.text-center Son todos aquellos datos que le conciernen a un interés general. Entre ellos se encuentran las sentencias judiciales y otros.   
          .hr_divider.m-auto

    .row.justify-content-start.bannerTema3--bg.mb-5            
      .col-lg-9
        .crd--banner
          p.mb-0 Por todo lo mencionado, durante una interacción con un cliente o deudo debe manifestarle el uso de la información que ha dado para iniciar el traslado del cadáver. Él debe saber qué datos se tienen de él, actualizar la información recolectada, rectificar aquella información que presente errores y eliminar información que no ha autorizado. Recuerde que la información que tenga del fallecido debe entrar en la cadena de custodia del proceso funerario.
    

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
