<template>
  <footer class="footer">
    <div class="container">
      <div class="footer__content">
        <div class="footer__logo">gks.</div>
        <div class="footer__meta">
          <p class="footer__text">
            <span class="code-style">IT-ремонт</span> = {
            <span class="arg">year: <span class="current-year">{2025}</span></span
            >, <span class="arg">location: "Екатеринбург"</span>}
          </p>
          <p class="footer__text">
            <span class="code-style">website</span> = {
            <span class="arg">design: "Константин Ганцев"</span>,
            <span class="arg">development: "Константин Ганцев"</span>}
          </p>
          <nav class="footer__nav">
            <a href="#home" class="footer__link">Главная</a>
            <a href="#services" class="footer__link">Услуги</a>
            <a href="#cases" class="footer__link">Примеры работ</a>
            <a href="#contacts" class="footer__link">Контакты</a>
          </nav>
          <div class="footer__social">
            <a href="https://t.me/gantsev_k" class="footer__link" aria-label="Telegram">
              <span class="code-style">telegram.connect(</span>@gantsev_k<span class="code-style"
                >)</span
              >
            </a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script setup lang="ts"></script>

<style scoped>
@import './footer.css';
</style>
