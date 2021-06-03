<template>
  <div class="container">
    <div class="flex-wrap">
      <div class="flex-column-logo">
        <img src="../static/img/logo.png" alt="logo" />
        <h2 class="logo-title">UKM</h2>
      </div>

      <div class="flex-column">
        <div class="flex-item">
          <h4 class="flex-item-title">Контакты</h4>
        </div>
        <div class="flex-item">
          <p>
            <span> Адрес:</span> Филиал / Склад Ташкент: Джурджоний 1,
            Учтепинский район, Ташкент, Узбекистан.
          </p>
        </div>
        <div class="flex-item"><span>Телефон:</span> +998652222911</div>
        <div class="flex-item"><span>Email:</span> uz_medical@mail.ru</div>
        <div class="flex-item">
          <span class="icon"
            ><i class="fa fa-facebook" aria-hidden="true"></i
          ></span>
          <span class="icon"
            ><i class="fa fa-instagram" aria-hidden="true"></i
          ></span>
          <span class="icon"
            ><i class="fa fa-telegram" aria-hidden="true"></i
          ></span>
        </div>
      </div>
      <div class="flex-column">
        <div class="flex-item"><h4 class="flex-item-title">О нас</h4></div>
        <div class="flex-item">О компании</div>
        <div class="flex-item">Продукция</div>
        <div class="flex-item">Контакты</div>
        <div class="flex-item">Новости</div>
      </div>
      <div class="flex-column">
        <div class="flex-item"><h4 class="flex-item-title">Продукция</h4></div>
        <div class="flex-item">Шприцы одноразовые</div>
        <div class="flex-item">Система для инфуз. растворов</div>
        <div class="flex-item">Инсулиновый шприц</div>
        <div class="flex-item">Гинекологическое зеркало</div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.flex-wrap {
  display: flex;
  justify-content: space-around;
  margin-top: 50px;
}
.flex-column-logo {
  display: flex;
  align-items: flex-start;
}
.flex-column {
  max-width: 330px;
}
.flex-item {
  margin-bottom: 20px;
}
.flex-item-title {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 22px;
  /* identical to box height */

  text-transform: capitalize;

  color: #242365;
}
.flex-item {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 23px;
  /* identical to box height, or 144% */

  text-transform: capitalize;

  color: #212121;
}
.flex-item span {
  color: #242365;
}
.icon {
  margin-right: 33px;
}
</style>