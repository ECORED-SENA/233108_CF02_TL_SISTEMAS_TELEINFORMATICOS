<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      p Una vez se ha reconocido la importancia sobre la responsabilidad y acciones que se deben para salvaguardar los activos informáticos ante ataques de ciberseguridad, se sintetiza cada uno de los aspectos desarrollados:
      .row.justify-content-center
        .col-lg-12.mb-5.bgs.p-4.brad
          figure
            img(src="@/assets/curso/sintesis.svg", alt="Imagen que muestra síntesis del componente formativo, indicando que la gestión de riesgos involucra dos aspectos:<br>1. La gestión de la información que busca proteger los activos por medio de programas, sistemas de información sensibles y redes.<br>2. La protección de datos que busca proteger de ataques informáticos como robo de información, sistemas caídos y denegación de servicio.<br>Ambos aspectos se reportan en informes técnicos.")
        .col-auto
          a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
            .anexo__icono
              img(src="@/assets/bullets/icono-pdf.svg")
            .anexo__texto
              p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
