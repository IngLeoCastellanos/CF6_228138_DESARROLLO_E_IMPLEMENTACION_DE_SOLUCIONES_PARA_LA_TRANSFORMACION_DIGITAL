<template lang="pug">
  .curso-main-container.pb-3.tema1
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      .titulo-principal.color-acento-botones
        .titulo-principal__numero
          span 2
        h1 Redes de Datos

</template>

<script>
export default {
  name: "Tema2",
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh();
    });
  },
  updated() {
    this.$aosRefresh();
  }
};
</script>

<style lang="sass"></style>
