<template>
  <div class="container">
    <div class="flex-wrap">
      <div class="flex-item">
        <img src="../../static/img/about.png" alt="about" />
      </div>
      <div class="flex-item">
        <div class="card">
          <h4 class="flex-item-title">О компании</h4>
          <p class="flex-item-text">
            СП ООО «Uz-Korea Medical» Совместное предприятие «Uz-Korea Medical»
            ведет свою успешную деятельность на рынке Узбекистана начиная с 2003
            года. За этот период предприятие зарекомендовало себя как
            ответственный и не останавливающийся в развитии производитель
            изделий медицинского назначения самого высокого уровня, отвечающей
            всем мировым стандартам качества и, конечно же, запросам
            отечественного потребителя.
          </p>
          <div class="flex-item-link"> <a href="#" >Подробное</a></div>
         
        </div>
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
  padding-bottom: 50px;
}
.flex-item {
    width: 50%;
}

.card {
  max-width: 655px;
  background-color: #f5f9fa;
  padding: 50px 50px;
  border-radius: 20px;
}
.flex-item-text {
  width: 550px;
  font-family: Montserrat;
font-style: normal;
font-weight: normal;
font-size: 18px;
line-height: 30px;

/* or 167% */


color: #212121;
}
.flex-item img {
  max-width: 450px;
}
.flex-item-title {
  font-family: Montserrat;
  font-style: normal;
  font-weight: 600;
  font-size: 28px;
  line-height: 27px;
  margin-bottom:30px ;
  /* identical to box height, or 96% */

  color: #242365;
}
.flex-item-link{
    text-align: right;
}

</style>