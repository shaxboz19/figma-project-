<template>
  <div class="container">
    <div class="flex-wrap">
      <div class="flex-item">
        <h3 class="flex-item-title">
          Иглы к шприц-ручкам: какие лучше? Мы поможем разобраться!
        </h3>
        <p class="flex-item-text">
          Шприцы одноразовые, Система для инфуз. растворов, Инсулиновый шприц,
          Гинекологическое зеркало
        </p>
        <button class="flex-item-button">Каталог</button>
      </div>
      <div class="flex-item">
        <img src="../../static/img/bg1.png" alt="bg1" />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>


<style scoped>
.flex-wrap {
  display: flex;
  height: 834px;
  align-items: center;
}
.flex-item {
  max-width: 50%;
}
.flex-item-title {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 600;
  font-size: 40px;
  line-height: 55px;
  color: #242365;
  margin-bottom: 40px;
}
.flex-item-text {
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 27px;
  /* or 150% */

  color: #212121;
}
.flex-item-button {
  background: #242365;
  border-radius: 35px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 22px;
  color: #ffffff;
  padding: 13px 68px;
  margin-top: 45px;
}
.flex-item-text{
  max-width: 300px;
}
</style>