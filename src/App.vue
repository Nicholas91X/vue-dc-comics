<template>
  <div id="app">
      <Header/>
      <Main/>
      <Footer/>
  </div>
</template>

<script>
import Header from "../src/components/macro/Header.vue";
import Main from "../src/components/macro/Main.vue";
import Footer from "../src/components/macro/Footer.vue";

export default {
  name: 'App',
  components: {
      Header,
      Main,
      Footer
  }
}
</script>


<style lang="scss">
@import "../src/assets/style/global.scss";
@import "../src/assets/style/partials/variables.scss";
</style>
