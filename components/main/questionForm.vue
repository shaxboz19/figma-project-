<template>
  <div class="container">
    <div class="question__wrapper">
      <div class="row mt">
        <div class="col mr">
          <h2 class="question__title">Остались вопросы?</h2>
          <p class="question__text">
            Заполните форму и мы обязательно свяжемся с вами
          </p>
          <p class="question__tel">+998 65 222 29 11</p>
          <div class="question__icons">
            <span class="question__icons-item"
              ><i class="fa fa-facebook" aria-hidden="true"></i
            ></span>
            <span class="question__icons-item"
              ><i class="fa fa-instagram" aria-hidden="true"></i
            ></span>
            <span class="question__icons-item"
              ><i class="fa fa-telegram" aria-hidden="true"></i
            ></span>
          </div>
        </div>
        <div class="col">
          <div class="question__form-input">
            <input type="text" placeholder="Имя" />
            <input type="email" placeholder="Email" />
          </div>
          <div class="question__form-input">
            <input type="tel" placeholder="Телефон" />
            <input type="text" placeholder="Сообщение" />
          </div>
          <div class="question__form-button">
            <button class="btn">Отправить</button>
          </div>
          <small class="question__small-text"
            >Нажимая на кнопку «Отправить», вы подтверждаете, что предоставляете
            Компании свое согласие на обработку ваших персональных данных</small
          >
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {};
</script>

<style scoped>
</style>