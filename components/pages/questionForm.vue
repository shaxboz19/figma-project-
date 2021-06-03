<template>
  <div class="container">
    <div class="flex-wrap">
      <div class="flex-item">
        <h2 class="title">Остались вопросы?</h2>
        <p class="text">Заполните форму и мы обязательно свяжемся с вами</p>
        <p class="telephone">+998 65 222 29 11</p>
        <div class="icons">
          <div class="icons-item"><i class="fa fa-facebook" aria-hidden="true"></i></div>
          <div class="icons-item"><i class="fa fa-instagram" aria-hidden="true"></i></div>
          <div class="icons-item"><i class="fa fa-telegram" aria-hidden="true"></i></div>
        </div>
      </div>
      <div class="flex-item">
        <div>
          <input type="text" placeholder="Имя" />
          <input type="email" placeholder="Email" />
        </div>
        <div>
          <input type="tel" placeholder="Телефон" />
          <input type="text" placeholder="Сообщение" />
        </div>

        <button class="btn">Отправить</button>
        <small
          >Нажимая на кнопку «Отправить», вы подтверждаете, что предоставляете
          Компании свое согласие на обработку ваших персональных данных</small
        >
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
  margin-top: 250px;
}
input {
  outline: none;
  border: none;
  border-bottom: 0.2px solid #0ab0f1;
}
.title {
  font-size: 35px;
  margin-bottom: 35px;
}
.text {
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 26px;
  margin-bottom: 40px;
  /* or 144% */

  color: #212121;
}
.telephone {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 500;
  font-size: 38px;
  line-height: 46px;
  letter-spacing: 0.02em;
    margin-bottom: 19px;
  color: #242365;
}
.icons-item{
    width: 42px;
    height: 42px;
    border-radius: 50%;
    background-color: #F5F9FA;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #242365;
    margin-right: 18px;
}
.icons-item:last-child{
    margin-right: 0;
}
.icons{
    display: flex;
}
</style>