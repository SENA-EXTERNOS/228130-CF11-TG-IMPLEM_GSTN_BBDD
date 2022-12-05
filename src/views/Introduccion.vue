<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.justify-content-center.mb-5
      .col-lg-4.col-4(data-aos="fade-right").mb-lg-0.mb-3: img(src='@/assets/curso/temas/intro/1.svg', alt='')
      .col-lg-8(data-aos="fade-left") 
        p Estimado aprendiz, sea bienvenido a este componente formativo, basado en las siguientes temáticas: Gestión de redundancia de servidores, Ciberseguridad, Gestión de clientes, Bitácoras, Informes de auditoría y Gestión de tecnologías de la información. A lo largo de este ciclo educativo, se estudiarán, así mismo, varios autores reconocidos en estos temas para obtener una mayor compresión de los mismos. Se invita a visualizar el siguiente video para identificar el contexto de aprendizaje.
          br
          br
          |#[b ¡Muchos éxitos en este proceso!]
    figure
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
