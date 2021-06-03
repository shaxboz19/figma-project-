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
import mainPage from "@/components/pages/mainPage";
import appCards from "@/components/pages/card";
import appAbout from '@/components/pages/about'
import appCatalog from '@/components/pages/catalog'
import appNews from '@/components/pages/news'
import appPartners from "@/components/pages/parners"
import appContacts from '@/components/pages/contacts'
import appForm from '@/components/pages/questionForm'
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
