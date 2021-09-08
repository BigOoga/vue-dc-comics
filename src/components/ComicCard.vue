<template>
  <div
    class="
  comic-card px-3 py-3"
  >
    <img :src="src" alt="" />
    <h4>{{ title }}</h4>
  </div>
</template>

<script>
export default {
  name: "ComicCard",
  props: ["src", "title"],
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
}
</style>
