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
      <li><fa icon='envelope' /></li>
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
* {
  color: #ffffff;
}

.navbar {
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 100px;
  width: 100%;
  background: #242365;
}
.navbar-list {
  display: flex;
  list-style: none;
}
.navbar-list li {
  margin-right: 70px;
  font-family: Montserrat;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 22px;
  /* identical to box height */

  text-transform: capitalize;
}
.navbar-list li:last-child {
  margin-right: 0;
}
.navbar-title {
  font-family: Montserrat;
  font-style: normal;
  font-weight: bold;
  font-size: 18px;
  line-height: 22px;
  /* identical to box height */

  text-transform: capitalize;
}
.navbar-logo {
  display: flex;
  align-items: center;
}
.dropdown * {
  color: #242365;
}
.navbar-logo-img {
  border-radius: 9px;
  margin-right: 13px;
}
</style>