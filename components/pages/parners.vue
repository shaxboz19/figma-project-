<template>
    <div class="container">
        <h2 class="title">Нам доверяют</h2>
        <div class="flex-wrap">
            <div class="flex-item" v-for="item of cards" :key="item">
                <img :src="item.link" alt="img">

            </div>
        </div>
        
    </div>
</template>

<script>
export default {
    data() {
        return {
            cards : [
                {link:require('@/static/img/partners6.png') },
                {link:require('@/static/img/partners2.png') },
                {link:require('@/static/img/partners3.png') },
                {link:require('@/static/img/partners4.png') },
                {link:require('@/static/img/partners5.png') },
                {link:require('@/static/img/partners1.png') },
            ]
        }
    },
    
}
</script>

<style scoped>
.flex-wrap{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 50px;
    margin-bottom: 130px;
}
.flex-item{
    margin-right: 30px;
    justify-content: center;
  
    
}
.flex-item:last-child{
    margin-right: 0;

}
</style>