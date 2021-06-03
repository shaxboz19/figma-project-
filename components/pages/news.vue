<template>
  <div class="container">
    <h3 class="title">Новости</h3>
    <div class="flex-wrap">
      <div class="flex-item" v-for="(item, index) in cards" :key="index">
        <img :src="item.link" alt="img" />
        <div class="small-text">
          <small>{{ new Date().toLocaleString() }}</small>
          <small><i class="fa fa-eye" aria-hidden="true"></i> 25</small>
        </div>
        <p class="flex-item-text">
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
.flex-wrap {
  display: flex;
  margin-top: 50px;
  margin-bottom: 100px;
}
.flex-item {
  width: 330px;
  margin-right: 30px;
}
.flex-item:last-child {
  margin-right: 0;
}
.flex-item-text {
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 25px;
  /* or 139% */

  color: #000000;
}
.small-text {
    display: flex;
    justify-content: space-between;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 20px;
  /* identical to box height */

  color: rgba(38, 38, 38, 0.7);
}
</style>