<template lang="pug">
  .curso-main-container.introduccion
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido(data-aos="flip-up")
        .titulo-principal__numero
          span
            i.fas.fa-info
        h1 Introducción
      .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-right")
        .bloque-texto-g__img(
          :style="{ backgroundImage: `url(${require_src('@/assets/curso/temas/intro/img1.png')})` }")
        .bloque-texto-g__texto.p-4
          p.mb-0 Los marcos de gestión de riesgos de ciberseguridad deben basarse en los estándares y las mejores prácticas de la industria; por tanto, su cumplimiento debe ser fundamental. Se debe tener en cuenta en su establecimiento las pautas y las metodologías de prueba de penetración presentadas en los marcos comunes de gestión de riesgos, como el Estándar de seguridad de datos PCI (PCI <i>Security Standards Council</i>, 2018), ISO/IEC 27001 y 27002 (Organización internacional de normalización, 2013a, 2013b), los Controles de seguridad críticos de CIS (Centro para la seguridad de Internet, 2021) y el Marco NIST para mejorar la ciberseguridad de la infraestructura crítica (Instituto Nacional de Estándares y Tecnología, 2018). Basado en lo anterior, el siguiente video expone la importancia de la gestión de riesgos en una organización:
      figure(data-aos="fade-left")
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/e5qt6pPkGbg" title="La gestión de riesgos" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

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
