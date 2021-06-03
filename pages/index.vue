<template>
  <div>
    <div class="header">
      <main-page></main-page>
    </div>
    <div class="main">
        <app-cards></app-cards>
        <app-about></app-about>
        <app-catalog></app-catalog>
        <app-news></app-news>
        <app-partners></app-partners>
        <app-contacts></app-contacts>
        <app-form></app-form>
        
    
    </div>
  </div>
</template>

<script>
import mainPage from "@/components/main/mainPage";
import appCards from "@/components/main/card";
import appAbout from '@/components/main/about'
import appCatalog from '@/components/main/catalog'
import appNews from '@/components/main/news'
import appPartners from "@/components/main/parners"
import appContacts from '@/components/main/contacts'
import appForm from '@/components/main/questionForm'
export default {
  components: {
    mainPage,
    appCards,
    appAbout,
    appCatalog,
    appNews,
    appPartners,
    appContacts,
    appForm


  },
};
</script>

<style>
.header {
  background-color: #f5f9fa;
}
</style>
