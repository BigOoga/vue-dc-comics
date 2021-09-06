<template>
  <div id="app">
    <Header />
    <Products />
    <Services />
    <Footer />
    <BottomFooter />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Products from "@/components/Products.vue";
import Services from "@/components/Services.vue";
import Footer from "@/components/Footer.vue";
import BottomFooter from "@/components/BottomFooter.vue";
export default {
  name: "App",
  components: {
    Header,
    Products,
    Services,
    Footer,
    BottomFooter,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
