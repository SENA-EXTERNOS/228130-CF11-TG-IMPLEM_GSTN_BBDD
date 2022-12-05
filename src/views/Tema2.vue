<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Ciberseguridad
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-1.col-6(data-aos="fade-right"): img(src='@/assets/curso/temas/tema2/1.svg', alt='')
      .col-lg-11
        p Se presenta a continuación la información sobre la ciberseguridad, ciberataques más comunes, amenazas, protección de ataques y la implementación de un SGSI (Sistema de Gestión de Seguridad de la Información).
    .tarjeta.mb-5.p-lg-5.p-3(style="background-color: #f1f8ff ")
      SlyderA(tipo='b')
        .row.px-lg-3.p-2
          .col-lg-6.mb-4.mb-md-0
            h5 Definición
            p Capa de protección, a partir de ella se trabaja para prevenir todo tipo de amenazas externas, las cuales ponen en riesgo los datos. Cabe resaltar que la seguridad informática no se refiere únicamente a la tecnología para prevenir ataques, sino también, a desarrollar estrategias de prevención que ayudan a la seguridad. No es una novedad, pero los ataques informáticos cada vez son más comunes, ya que la mayoría de la información se maneja digitalmente.
              br
              br
              |Este término generalmente, se relaciona con ciberamenazas y al cibercrimen. Sin embargo, también tiene que ver con la manera como se protege la información y se puede prever ataques cibernéticos, a los que están expuestas las empresas o personas. Estas amenazas de seguridad informática usualmente llegan por los programas dañinos o malware, que son implantados en los equipos o dispositivos por medio de la nube (Cardado, 2018).
          .col-lg-6.col-8
            figure
              img(src='@/assets/curso/temas/tema2/2.jpg', alt='Texto que describa la imagen' style='border-radius: 10px')
        .row.px-lg-3.p-2
          .col-lg-6.mb-4.mb-md-0
            h5 Ciberataques más comunes
            ul.lista-ul--color
              li
                i.fas.fa-check
                p.mb-0 #[b El #[em ransomware]: se]destaca por su capacidad de restringir el acceso a un sistema informático y pedir un rescate para eliminar el bloqueo, este tipo de ciberataque es crítico para cualquier empresa, ya que puede ocasionar una pérdida de datos de gran importancia, ocasionando incluso perjuicios económicos.
              li
                i.fas.fa-check
                p.mb-0 #[b Ataque de denegación de servicio:] consiste en ocasionar una caída del servidor sobrecargando su tráfico de red y generando una caída en su ancho de banda. También son utilizadas para inundar masivamente el tráfico de servicios en línea de los bancos y otras entidades financieras, generando como resultado la caída del servidor (Arroyo et al, 2020).
              li
                i.fas.fa-check
                p.mb-0 #[b Troyanos:] estos se instalan en cualquier dispositivo solo con visitar un sitio web infectado, también por descargar el adjunto de un correo electrónico o por descargar una aplicación. Una vez que este virus se instala en el celular, es capaz de saber el momento preciso en que se utilizan los servicios en línea de aplicaciones bancarias, obteniendo credenciales personales y datos bancarios.
          .col-lg-6.col-8
            figure
              img(src='@/assets/curso/temas/tema2/3.jpg', alt='Texto que describa la imagen' style='border-radius: 10px')
        .row.px-lg-3.p-2
          .col-lg-6.mb-4.mb-md-0
            h5 Amenazas
            p La ciberseguridad día tras día, enfrenta las amenazas que se mencionan a continuación:
            ul.lista-ul--color
              li
                i.fas.fa-check
                p.mb-0 Delito cibernético: son agentes personas o grupos, que violan sistemas informáticos, estos pueden llegar a causar fallas en los sistemas y así obtienen beneficios financieros.
              li
                i.fas.fa-check
                p.mb-0 Ciberataques: estos generalmente atacan a servidores en búsqueda de información con fines políticos.
              li
                i.fas.fa-check
                p.mb-0 Ciberterrorismo: este se basa en debilitar sistemas informáticos, de esta manera generar pánico o terror.
          .col-lg-6.col-8
            figure
              img(src='@/assets/curso/temas/tema2/4.jpg', alt='Texto que describa la imagen' style='border-radius: 10px')
        .row.px-lg-3.p-2
          .col-lg-6.mb-4.mb-md-0
            h5 Prevención
            p Para prevenir ataques es necesario evitar aquellas publicidades y amenazas, que son enviadas a través de los correos electrónicos, ya que mediante los e-ails se pueden introducir amenazas de virus y robo de la información. Es por esto que se recomienda el monitoreo de las actividades de mensajes sospechosos, los remitentes anónimos y los dominios extraños. Asimismo, educar al personal de la empresa sobre el buen uso de este medio.
              br
              br
              |Es necesario detectar a tiempo códigos maliciosos, hay extensiones comunes donde se alojan estos virus como lo son: PDF, HTML, gif y zip, por esto es fundamental escoger un buen antivirus que sea capaz de descubrir esos códigos maliciosos y evitar el robo de los datos. También se debe ser capaz de reconocer aquellas conexiones sospechosas; por ello es necesario de utilizar herramientas que analicen la reputación de las fuentes no confiables.
          .col-lg-6.col-8
            figure
              img(src='@/assets/curso/temas/tema2/5.jpg', alt='Texto que describa la imagen' style='border-radius: 10px')
        .row.px-lg-3.p-2
          .col-lg-6.mb-4.mb-md-0
            h5 Prevención
            p Otra forma de prevenir ataques a las bases de datos es utilizando herramientas que analicen los datos y el registro de ingresos no autorizados. Generalmente los intentos no autorizados, pueden ser una señal para dar una alerta, de que la red podría estar amenazada. Por esta razón, es importante tener el sistema actualizado, ya que este proporcionará un mejor soporte frente a la seguridad informática. Entre más antiguo sea un sistema, tendrá mayores probabilidades de ser atacado, debido a que proporcionarán tecnologías rústicas de protección contra intrusos (Cardador, 2018).
          .col-lg-6.col-8
            figure
              img(src='@/assets/curso/temas/tema2/6.jpg', alt='Texto que describa la imagen' style='border-radius: 10px')
        .row.px-lg-3.p-2
          .col-lg-6.mb-4.mb-md-0
            h5 Protección del usuario
            p La protección del usuario final es un aspecto clave en la ciberseguridad, es por esto que se utilizan protocolos criptográficos para cifrar los correos electrónicos, archivos y datos importantes. La ciberseguridad no solamente protege la información que se mueve, también permite la recuperación de información. El software de seguridad que utiliza el usuario final debe ser capaz de analizar, detectar código malicioso, poner en cuarentena y eliminarlo del equipo, este, además debe ser idóneo para descubrir código malicioso oculto, en el registro de arranque maestro (Zain et al, 2019).
          .col-lg-6.col-8
            figure
              img(src='@/assets/curso/temas/tema2/7.jpg', alt='Texto que describa la imagen' style='border-radius: 10px')
        .row.px-lg-3.p-2
          .col-lg-6.mb-4.mb-md-0
            h5 Protección de ataques
            p En la actualidad no existe nada seguro. Sin embargo, si se hace énfasis en capacitar al usuario final acerca de cómo prevenir ciberataques, se podrían mitigar estos efectos. Por ello, son primordiales las acciones como: actualizar el software, utilizar un buen antivirus, mejorar las contraseñas, establecer políticas en los correos electrónicos y evitar el uso de redes wifi en lugares públicos. Estas son las recomendaciones a seguir, para poder garantizar la seguridad.
          .col-lg-6.col-8
            figure
              img(src='@/assets/curso/temas/tema2/8.jpg', alt='Texto que describa la imagen' style='border-radius: 10px')
        .row.px-lg-3.p-2
          .col-lg-6.mb-4.mb-md-0
            h5 Estándares de seguridad
            p El SGSI es un conjunto de normativas de administración de la información, se apoya en el estándar internacional ISO/IEC 27001. Este especifica los requisitos necesarios para mantener y mejorar un sistema de gestión de seguridad de la información, el estándar se enfoca en la mejora continua, planificar, hacer, controlar y actuar. El SGSI siempre buscará la accesibilidad de la información, asegurando la confidencialidad, integridad y disponibilidad (Zain et al, 2019).
              br
              br
              |Como en todo proceso de gestión, debe ser capaz de adaptarse a los cambios internos de la organización y también a los cambios del entorno.
              br
              br
              |Los controles se hacen para mitigar los riesgos de los datos de la organización, algunos de ellos pueden ser: el uso de una política, que requiera la utilización de VPN, tarjetas de acceso para ingresar a algún sitio y el uso de software antivirus (Zain et al, 2019).
          .col-lg-6.col-8
            figure
              img(src='@/assets/curso/temas/tema2/9.jpg', alt='Texto que describa la imagen' style='border-radius: 10px')
        .row.px-lg-3.p-2
          .col-lg-6.mb-4.mb-md-0
            h5 Implementación de un SGSI
            p Se deben crear políticas de seguridad de la información, al igual que un plan de tratamiento de riesgos, luego se define el alcance y lo que cubrirá, para establecer un método que permita identificar riesgos y poder evaluar qué riesgos se aplican al negocio, mientras se definen los controles relacionados con estos.
              br
              br
              |Finalmente, se documenta y se hace un seguimiento de los esfuerzos de mitigación, para poder llegar a realizar revisiones y retroalimentación del SGSI. Todo esto brindará grandes beneficios a las organizaciones, como la confianza y la satisfacción de los requisitos de seguridad de la información. Además, se pueden gestionar los activos de información de manera organizada para que facilite la mejora, igualmente, que reduce el riesgo de pérdida, robo o corrupción de la información. Otras ventajas son:
          .col-lg-6.col-8
            figure
              img(src='@/assets/curso/temas/tema2/10.jpg', alt='Texto que describa la imagen' style='border-radius: 10px')
        .row.px-lg-3.p-2
          .col-lg-6.mb-4.mb-md-0
            h5 Implementación de un SGSI
            ul.lista-ul--color
              li
                i.fas.fa-check
                p.mb-0 Reducción de riesgos en la información.

              li
                i.fas.fa-check
                p.mb-0 Reducción de impactos de incidentes en la seguridad.

              li
                i.fas.fa-check
                p.mb-0 Certificación de una estándar internacional.

              li
                i.fas.fa-check
                p.mb-0 Focaliza el gasto en seguridad de la información.
          .col-lg-6.col-8
            figure
              img(src='@/assets/curso/temas/tema2/11.jpg', alt='Texto que describa la imagen' style='border-radius: 10px')
    p.mb-5(data-aos='fade-right') A continuación, se dan a conocer algunos métodos utilizados para amenazar los sistemas:
    .row.justify-content-center.mb-5
      .col-lg-10(data-aos="zoom-in")
        .titulo-sexto.color-acento-contenido(data-aos='fade-right')
          h5 Figura 2.
          br
          span.fst-italic Métodos para amenazar los sistemas
        ImagenInfografica.color-primario.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/tema2/12.svg', alt='Texto que describa la imagen')
          .tarjeta.p-3(x="7%" y="80%" numero="" style="background-color: #ffecc1 ")
            .text-center
              .h5.mb-2 #[em Malware]
              p Se define como un #[em software] que tiene código malicioso, encabeza la lista ya que es unos de los métodos más comunes para el robo o daño de la información. Estos softwares son creados por un #[em hacker] y tienen como función infiltrarse en correos electrónicos fácilmente, para luego ganar dinero o robar algún tipo de información.
          .tarjeta.p-3(x="24.5%" y="80%" numero="" style="background-color: #ffecc1 ")
            .text-center
              .h5.mb-2 Virus
              p Es un #[em software] capaz de copiarse a sí mismo, se incrusta en algún archivo y luego se extiende en todo el sistema, infectando a cada uno de los archivos utilizando un código malicioso.
          .tarjeta.p-3(x="41.5%" y="80%" numero="" style="background-color: #ffecc1 ")
            .text-center
              .h5.mb-2 Troyanos
              p Es capaz de esconderse y darse a conocer como si fuera una aplicación original, los cibercriminales utilizan los troyanos para engañar a los usuarios y así estos puedan dañar un sistema informático.
          .tarjeta.p-3(x="58.4%" y="80%" numero="" style="background-color: #ffecc1 ")
            .text-center
              .h5.mb-2 #[em Spyware] 
              p Son aplicaciones con características muy específicas, estos se encargan de robar la información en secreto y enviarla a los #[em hackers.] Podría capturar lo que se escribe, los datos de las tarjetas de crédito, entre otros.
          .tarjeta.p-3(x="75.4%" y="80%" numero="" style="background-color: #ffecc1 ")
            .text-center
              .h5.mb-2 #[em Ransomware]
              p Este tipo de #[em software] bloquea los archivos del usuario y amenaza con borrarlos del sistema, hasta que haga un pago por el rescate de la información.
          .tarjeta.p-3(x="92.8%" y="80%" numero="" style="background-color: #ffecc1 ")
            .text-center
              .h5.mb-2 #[em Adware]
              p Es uno de los #[em softwares] más comunes, ya que se encuentra mucho en las publicidades de aplicaciones y sitios web. Este es capaz de insertar un #[em malware].


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
