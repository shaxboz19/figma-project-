<template>
  <div class="container">
    <h2 class="title">Каталог</h2>
    <div class="flex-wrap">
      <div class="flex-item" v-for="item of cards" :key="item">
        <div class="flex-item-img">
          <img :src="item.link" alt="card" />
        </div>

        <p class="flex-item-text">
          Шприцы одноразовые 1 мл Блстерная упаковка Игла 0.4 серая игла
        </p>
        <button class="btn">Подробнее</button>
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
.flex-wrap {
  display: flex;
  flex-wrap: wrap;
  margin-bottom: 100px;
}
.flex-item {
  width: 330px;
  background-color: #f5f9fa;
  border-radius: 20px;
  margin-top: 100px;
  margin-right: 30px;
  padding-bottom: 22px;
}
.flex-item:nth-child(4),
.flex-item:nth-child(8) {
  margin-right: 0;
}
.flex-item-text {
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 25px;
  padding: 0 30px;
  /* or 156% */

  color: #212121;
}
.btn {
  margin-left: 30px;
  text-align: center;
}
.flex-item-img {
  text-align: center;
  transform: translateY(-50px);
}
.title{
    margin-bottom: 50px;
}

</style>
