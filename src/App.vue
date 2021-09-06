<template>
  <div id="app">
    <Header />
    <Products />
    <Services />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Products from "@/components/Products.vue";
import Services from "@/components/Services.vue";
export default {
  name: "App",
  components: {
    Header,
    Products,
    Services,
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
