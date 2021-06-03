<template>
  <nav class="navbar">
    <div class="navbar-logo">
      <img src="../static/img/logo.png" alt="logo" class="navbar-logo-img" />

      <h2 class="navbar-title">UKM</h2>
    </div>
    <ul class="navbar-list">
      <li>О компании</li>
      <li>Каталог</li>
      <li>Новости</li>
      <li>Контакты</li>
      <li>
        <el-dropdown>
          <span class="el-dropdown-link">
            Ру<i class="el-icon-arrow-down el-icon--right"></i>
          </span>
          <el-dropdown-menu slot="dropdown" class="dropdown">
            <el-dropdown-item>En</el-dropdown-item>
            <el-dropdown-item>Uzb</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
      </li>
    </ul>
  </nav>
</template>

<script>
export default {};
</script>

<style lang="css" scoped>

</style>