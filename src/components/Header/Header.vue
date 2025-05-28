<template>
  <header class="header" role="banner">
    <h1 class="header-logo">
      <span class="logo-text">Ремонт компьютеров и IT-услуги</span>
      <span class="logo-abbr" aria-label="Константин Ганцев, Екатеринбург">gks.</span>
    </h1>
    <NavBar />
    <p class="header-subtitle">
      <span class="header-subtitle__text">PC Repair</span>
      <span title="Гарантия качества">100%</span>
    </p>
  </header>
</template>

<script setup lang="ts">
import NavBar from '../NavBar/Nav.vue'
</script>

<style scoped>
@import './header.css';
</style>
