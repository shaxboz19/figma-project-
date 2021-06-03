<template>
  <div class="container">
    <h2 class="catalog-title">Каталог</h2>
    <div class="catalog-flex-wrap">
      <div class="catalog-flex-item" v-for="item of cards" :key="item">
        <div class="catalog-flex-item-img">
          <img :src="item.link" alt="card" />
        </div>

        <p class="catalog-flex-item-text">
          Шприцы одноразовые 1 мл Блстерная упаковка Игла 0.4 серая игла
        </p>
        <button class="btn catalog-btn">Подробнее</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      cards: [
        { link: require("@/static/img/card1.png") },
        { link: require("@/static/img/card2.png") },
        { link: require("@/static/img/card3.png") },
        { link: require("@/static/img/card4.png") },
        { link: require("@/static/img/card5.png") },
        { link: require("@/static/img/card6.png") },
        { link: require("@/static/img/card7.png") },
        { link: require("@/static/img/card8.png") },
      ],
    };
  },
  mounted() {},
};
</script>

<style scoped>


</style>
