<template>
  <div id="services" class="d-flex justify-content-center align-items-center">
    <div class="container">
      <div class="d-flex justify-content-around">
        <a
          href="#"
          class="card d-flex justify-content-between align-items-center text-white mx-3"
          v-for="(service, index) in services"
          :key="index"
        >
          <div class="px-3"><img :src="service.src" alt="" /></div>
          <div>{{ service.text }}</div>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Services",
  data() {
    return {
      services: [
        {
          src: require("@/assets/img/buy-comics-digital-comics.png"),
          text: "Digital Comics",
        },
        {
          src: require("@/assets/img/buy-comics-merchandise.png"),
          text: "DC Merchandise",
        },
        {
          src: require("@/assets/img/buy-comics-subscriptions.png"),
          text: "Subscription",
        },
        {
          src: require("@/assets/img/buy-comics-shop-locator.png"),
          text: "Comic Shop Locator",
        },
        {
          src: require("@/assets/img/buy-dc-power-visa.svg"),
          text: "DC Power Visa",
        },
      ],
    };
  },
};
</script>

<style lang="scss">
@import "@/assets/scss/_generics.scss";
@import "@/assets/scss/style.scss";
</style>
