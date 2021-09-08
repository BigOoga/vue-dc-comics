<template>
  <div
    class="
  comic-card px-3 py-3 my-5"
  >
    <img :src="card.thumb" alt="" />
    <h4>{{ card.series }}</h4>
  </div>
</template>

<script>
export default {
  name: "ComicCard",
  props: {
    card: Object,
  },
};
</script>

<style scoped lang="scss">
img {
  height: 200px;
  width: 200px;
  object-fit: cover;
  object-position: top;
}

.comic-card {
  max-width: 200px;
  height: calc(200px + 36px);
}
</style>
