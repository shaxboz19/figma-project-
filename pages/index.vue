<template>
  <div>
    <div class="header">
      <main-page></main-page>
    </div>
    <div class="main">
        <app-cards></app-cards>
        <app-about></app-about>
    
    </div>
  </div>
</template>

<script>
import mainPage from "@/components/pages/mainPage";
import appCards from "@/components/pages/card";
import appAbout from '@/components/pages/about'
export default {
  components: {
    mainPage,
    appCards,
    appAbout,
  },
};
</script>

<style>
.header {
  background-color: #f5f9fa;
}
</style>
