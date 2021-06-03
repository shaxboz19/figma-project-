<template>
  <div class="container">
    <h3 class="news-title title">Новости</h3>
    <div class="news-flex-wrap">
      <div class="news-flex-item" v-for="(item, index) in cards" :key="index">
        <img :src="item.link" alt="img" />
        <div class="news-small-text">
          <small>{{ new Date().toLocaleString() }}</small>
          <small><i class="fa fa-eye" aria-hidden="true"></i> 25</small>
        </div>
        <p class="news-flex-item-text">
          {{ item.text }}
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      cards: [
        {
          link: require("../../static/img/news1.png"),
          text:
            "Робот получил лицензию врача Бот Сяо И сдал экзамен по медицине... ",
        },
        {
          link: require("../../static/img/news2.png"),
          text:
            "Во сколько обойдется зарубежным странам российская вакцина от COVID-19... ",
        },
        {
          link: require("../../static/img/news3.png"),
          text:
            "Давление медицинских чиновников на врачей недопустимо, уверены в ОНФ... ",
        },
        {
          link: require("../../static/img/news4.png"),
          text:
            "Оформление медицинской карты для детского сада или школы в Новосибирске... ",
        },
      ],
    };
  },
};
</script>

<style lang="css" scoped>

</style>