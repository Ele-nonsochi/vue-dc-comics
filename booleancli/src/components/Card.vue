<template>
  <div class="card">
    <div class="ratio">
      <div class="content">
        <img class="card__img" :src="thumbnail" alt="" />
      </div>
    </div>
    <p class="card__text">{{ title }}</p>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: {
    thumbnail: String,
    title: String,
  },
};
</script>

<style >

</style>