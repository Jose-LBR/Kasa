<script setup lang="ts"></script>

<template>
  <header>
    <div class="header-container d-flex justify-content-space-between">
      <div class="logo">Kasa</div>
      <nav class="b1">
        <router-link to="home" class="nav1">Accueil</router-link>
        <router-link to="about" lass="nav2">A Propos</router-link>
      </nav>
    </div>
  </header>
</template>

<style scoped lang="scss">
header {
  width: 1240px;
  height: 68px;
  position: absolute;
  left: 100px;
  top: 40px;

  .logo {
    width: 210.32px;
    height: 68px;
  }

  nav {
    width: 309px;
    height: 34px;
    position: relative;

    .nav1 {
      color: #ff6060;
      position: absolute;
      //   left: 75.08%;
      right: 13, 95%;
      top: 25%;
      bottom: 25%;
    }
  }
}
</style>
