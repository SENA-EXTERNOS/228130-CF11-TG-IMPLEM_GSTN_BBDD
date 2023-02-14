<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Gestión de clientes
    .row.justify-content-center.mb-5
      .col-lg-7.mb-lg-0.mb-3(data-aos="fade-right")
        p El mundo actual es exigente y está enmarcado en los requerimientos de calidad y atención que impone la nueva economía, por esta razón las empresas competitivas del día de hoy, se han enfocado en obtener éxito a través de la relación con los clientes, más allá de la rentabilidad empresarial o de un producto, es importante la interacción con el cliente, conocerlo y reconocer su valor. Por tanto, es necesario saber que le gusta, escuchar sus quejas, sugerencias y utilizar esta información en beneficio de la compañía, para poder garantizar la satisfacción y conseguir su lealtad hacia la empresa. Es allí donde las nuevas tecnologías permiten competir en los mercados de una manera mucho más eficiente, al tener la información disponible cuando se requiera y poder optimizar los recursos.
        .cajon.color-acento-contenido.p-4.mb-4(style="background-color: #fff4da")
          p A corto plazo, las empresas tendrán que aprender a medir la rentabilidad de cada cliente y cambiar el concepto organizacional en donde es el cliente el que tiene que ir por el producto (Fernández, #[em et al], 2014).

      .col-lg-5.col-8(data-aos="fade-left"): img(src='@/assets/curso/temas/tema3/1.png', alt='')
    .row.justify-content-center.mb-5
      .col-lg-4.col-8.mb-lg-0.mb-3(data-aos="fade-right"): img(src='@/assets/curso/temas/tema3/2.svg', alt='')
      .col-lg-8(data-aos="fade-left")
        p Toda organización debe contar con una mesa de servicio o ayuda, esta permitirá que cuando una infraestructura tecnológica presente incidentes pueda continuar su operación, la mesa de servicio interviene para corregir posibles fallas, también puede prevenir que se repitan en el futuro.
        p Además, la capacidad de una organización para tener una reacción inmediata por alguna falla y la prevención de problemas es fundamental para la gestión de soluciones, debido a esto se pueden crear estrategias para optimizar servidores, #[em hardware y software.]
        p Algunas de las ventajas a la hora de tener una mesa de servicio son:
        ul.lista-ul--color
          li
            i.fas.fa-check
            | Reducción de costos.
          li
            i.fas.fa-check
            | Certeza en los procesos de los empleados.
          li
            i.fas.fa-check
            | Mejora el tiempo de respuesta al usuario final.
          li
            i.fas.fa-check
            | Capacidad de enfoque en las metas.
    .row.justify-content-center.mb-5
      .col-lg-10(data-aos="zoom-in")
        .bloque-texto-g.p-3.p-sm-4.p-md-5(style="background-color: #ffe4a9")
            .bloque-texto-g__img(style="background-color: #ebebeb ").align-items-center.d-flex
              img(src='@/assets/curso/temas/tema3/3.svg', alt='' style='width: 350px').m-auto

            .bloque-texto-g__texto.p-4.border-dash.bg-transparent.p-4
              .bg-white.p-3
                p.mb-0 La mesa de servicio se encargará de brindar asistencia o asesoría a los clientes, en respuesta a una solicitud previa, brindándoles información y soluciones técnicas de manera rápida y eficaz. Cabe resaltar que la mesa de servicio hace las funciones de una mesa de ayuda, además de las características antes mencionadas.

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
