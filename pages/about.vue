<template>
  <div class="inner-wrapper">
    <section class="about">
      <div class="container">
        <div class="about__wrapper">
          <div class="about__breadcrumb">
            <el-breadcrumb separator="/">
              <el-breadcrumb-item :to="{ path: '/' }"
                ><span class="color">Главная</span></el-breadcrumb-item
              >
              <el-breadcrumb-item>О компании</el-breadcrumb-item>
            </el-breadcrumb>
          </div>
          <div class="row">
            <div class="col">
              <img src="../static/img/about/about1.png" alt="img" />
            </div>
            <div class="col">
              <div class="card about-width">
                <h2 class="card__title">О компании</h2>
                <p class="card__text">
                  UKM, официальное наименование JV LLC UZ-KOREA MEDICAL,
                  является результатом превосходного управления и плодотворного
                  партнерства. В течение долгих лет занятия бизнесом компания
                  UKM замечательно работала в области медицинской технологии на
                  рынке Узбекистана. После исследований, разработки и запуска
                  первых продуктов 10 апреля 2003 г., UКМ помогла поднять наших
                  работников на мировой уровень. Воодушевленные философией Ибн
                  Сино (Авиценны), наполненные энтузиазмом, осененные Великим
                  Шелковым Путем и поддержанные глобальным партнерством, мы с
                  гордостью вступаем в фазу стратегической глобализации нашего
                  вклада в здравоохранение. Нашей главной целью является
                  поставка качественных и доступных фармацевтических продуктов
                  нашим людям этическим, эффективным и наиболее профессиональным
                  путем
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="value">
      <div class="container">
        <div class="value__wrapper">
          <h2 class="value__title">Ценности</h2>
          <p class="value__text maxw471">
            Наши ценности включают глубочайшую веру и наши самые высокие
            стремления:
          </p>
          <div class="row pb17 sb">
            <div class="col ">
              <p class="value__text bold maxw541">
                Мы являемся амбициозной командой интеллектуально подготовленных
                новаторов
              </p>
            </div>
            <div class="col ">
              <p class="value__text bold maxw361">
                Подотчетность перед нашими клиентами и акционерами
              </p>
            </div>
          </div>
          <ul class="value__list">
            <li>Я Качество и доступность</li>
            <li>Я Честность без упрека</li>
            <li>Я Уважение к людям</li>
            <li>Я Готовность к выполнению нашей миссии</li>
            <li>Я Командная работа, пересекающая все границы</li>
            <li>Я Адаптация к вызовам и переменам</li>
          </ul>
        </div>
      </div>
    </section>
    <section class="mission">
      <div class="container">
        <div class="mission__wrapper">
          <div class="row sb">
            <div class="col ">
              <div class="card">
                <h2 class="mission__title">Миссия</h2>
                <p class="mission__text">
                  Мы поставляем миру фармацевтические и медицинские препараты,
                  которые улучшают жизнь и обеспечивают существенные ценности
                  наши клиентам и акционерам, улучшая доступность, безопасность
                  и качество
                </p>
              </div>
            </div>
            <div class="col">
              <img src="@/static/img/about/about2.png" alt="img" />
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="partners">
      <app-partners></app-partners>
    </section>
    <section class="certificate">
      <div class="container">
        <div class="certificate__wrapper">
          <h2 class="certificate__title">Наши сертификаты</h2>
          <div class="row alignend">
            <div class="col mr30">
              <img src="../static/img/about/certificate1.png" alt="img" />
            </div>
            <div class="col mr30">
              <img src="../static/img/about/certificate2.png" alt="img" />
            </div>
            <div class="col mr30">
              <img src="../static/img/about/certificate3.png" alt="img" class="mb28" />
              <img src="../static/img/about/certificate4.png" alt="img" />
            </div>
            <div class="col mr30">
              <img src="../static/img/about/certificate5.png" alt="img" />
            </div>
            <div class="col ">
              <img src="../static/img/about/certificate6.png" alt="img" />
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="question">
      <app-form></app-form>
    </section>
  </div>
</template>

<script>
import appPartners from "@/components/main/parners";
import appForm from "@/components/main/questionForm";
export default {
  components: {
    appPartners,
    appForm,
  },
  data() {
    return {};
  },
};
</script>