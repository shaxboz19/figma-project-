<template>
  <div class="container">
    <div class="partners__wrapper">
      <h2 class="partners__title title">Нам доверяют</h2>
      <div class="partners__flex-wrap">
        <div class="partners__flex-item" v-for="item of cards" :key="item">
          <img :src="item.link" alt="img" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      cards: [
        { link: require("@/static/img/partners6.png") },
        { link: require("@/static/img/partners2.png") },
        { link: require("@/static/img/partners3.png") },
        { link: require("@/static/img/partners4.png") },
        { link: require("@/static/img/partners5.png") },
        { link: require("@/static/img/partners1.png") },
      ],
    };
  },
};
</script>

<style scoped>
</style>