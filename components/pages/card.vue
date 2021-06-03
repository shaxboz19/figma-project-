<template>
  <div class="container">
    <div class="flex-wrap">
      <div class="flex-item">
        <div class="flex-item-logo">
          <img src="../../static/img/eye.svg" alt="eye" />
        </div>
        <h2 class="flex-item-title">ВИДЕНИЕ</h2>
        <p class="flex-item-text">
          Наше видение - это прокладывать путь в более здоровому миру
        </p>
      </div>
      <div class="flex-item">
        <div class="flex-item-logo">
          <img src="../../static/img/target.svg" alt="eye" />
        </div>
        <h4 class="flex-item-title">МИССИЯ</h4>
        <p class="flex-item-text">
          Мы поставляем миру фармацевтические и медицинские препараты, которые
          улучшают жизнь
        </p>
      </div>
      <div class="flex-item">
        <div class="flex-item-logo">
          <img src="../../static/img/hand.svg" alt="eye" />
        </div>
        <h4 class="flex-item-title">ЦЕННОСТИ</h4>
        <p class="flex-item-text">
          Наши ценности включают глубочайшую веру и наши самые высокие
          стремления
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="css" scoped>
.flex-wrap {
  display: flex;
  margin-top: 150px;
  padding-bottom: 108px;
}
.flex-item {
  width: 450px;
  height: 250px;
  padding: 0 35px;
  margin-right: 30px;
  text-align: center;
  background-color: #f5f9fa;
  border-radius: 20px;
 
}
.flex-item-logo {
  margin: 0 auto;
  width: 100px;
  height: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  background-color: #fff;
  transform: translateY(-50px);
}
.flex-item-title {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 500;
  font-size: 22px;
  line-height: 27px;
  /* identical to box height */

  color: #242365;
}
.flex-item-text {
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 25px;
  margin-top: 30px;
  /* or 139% */

  text-align: center;

  color: #212121;
}
</style>