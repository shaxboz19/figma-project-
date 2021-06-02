<template>
  <div class="layout">
    <header>
      <app-navbar></app-navbar>
    </header>

    <main><nuxt /></main>
    <footer class="footer">
      <app-footer></app-footer>
    </footer>
  </div>
</template>

<script>
import appNavbar from "../components/appNavbar";
import appFooter from "../components/appFooter";
export default {
  components: {
    appNavbar,
    appFooter,
  },
};
</script>

<style>
.layout {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  height: 100vh;
}
.footer {
  background-color: #f5f9fa;
  padding-bottom: 50px;
}
</style>
