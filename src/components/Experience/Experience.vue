<template>
  <section class="experience" id="about">
    <div class="container">
      <h2 class="experience__title">Мой подход <span class="code-style">> about_me()</span></h2>
      <div class="experience__container">
        <article class="experience__item">
          <div class="exp__header">
            <h3 class="exp__name">Профиль <span class="code-style">> profile()</span></h3>
          </div>
          <div class="exp__content">
            <p class="exp__descr">
              <span class="exp__key">// Опыт:</span>
              <span class="exp__value"
                >14+ лет системного администрирования и участия в разработке ПО</span
              >
            </p>
            <p class="exp__descr">
              <span class="exp__key">// Решаю:</span>
              <span class="exp__value"
                >Проблемы от домашних ПК до корпоративной инфраструктуры</span
              >
            </p>
            <p class="exp__descr">
              <span class="exp__key">// Экспертиза:</span>
              <span class="exp__value">Windows/Linux, виртуализация, резервное копирование</span>
            </p>
          </div>
        </article>

        <article class="experience__item">
          <div class="exp__header">
            <h3 class="exp__name">
              Философия работы <span class="code-style">> philosophy()</span>
            </h3>
          </div>
          <div class="exp__content">
            <p class="exp__descr">
              <span class="exp__key">//</span>
              <span class="exp__value"
                >Никакого "просто переустановите Windows" — устраняю первопричины проблем</span
              >
            </p>
            <ul class="exp__list">
              <li>Объясняю сложное простыми словами</li>
              <li>Научу избегать повторения проблем</li>
              <li>Подберу оптимальные решения под ваш бюджет</li>
            </ul>
          </div>
        </article>

        <!-- Блок 3: Процесс работы -->
        <article class="experience__item">
          <div class="exp__header">
            <h3 class="exp__name">Как я работаю <span class="code-style">> workflow()</span></h3>
          </div>
          <div class="exp__content">
            <ul class="exp__list">
              <li><strong>1. Диагностика</strong> — точное определение причины</li>
              <li><strong>2. План</strong> — согласование решения и стоимости</li>
              <li><strong>3. Реализация</strong> — быстрое и аккуратное исполнение</li>
              <li><strong>4. Обучение</strong> — объясню как избежать проблемы в будущем</li>
            </ul>
          </div>
        </article>

        <!-- Блок 4: Гарантии -->
        <article class="experience__item">
          <div class="exp__header">
            <h3 class="exp__name">Гарантии <span class="code-style">> warranty()</span></h3>
          </div>
          <div class="exp__content">
            <ul class="exp__list">
              <li>Исправление за свой счет, если проблема повторится</li>
              <li>Конфиденциальность ваших данных</li>
              <li>Честная оценка сроков и стоимости</li>
              <li>Поддержка после ремонта</li>
            </ul>
          </div>
        </article>

        <!-- Блок 5: Технологии -->
        <article class="experience__item">
          <div class="exp__header">
            <h3 class="exp__name">Методы <span class="code-style">> methods()</span></h3>
          </div>
          <div class="exp__content">
            <ul class="exp__list">
              <li>Глубокая диагностика системных ошибок</li>
              <li>Безопасное удаление сложных вирусов</li>
              <li>Восстановление данных без потерь</li>
              <li>Оптимизация для максимальной производительности</li>
            </ul>
          </div>
        </article>

        <!-- Блок 6: Призыв к действию -->
        <article class="experience__item">
          <div class="exp__header">
            <h3 class="exp__name">Готов помочь <span class="code-style">> contact_me()</span></h3>
          </div>
          <div class="exp__content">
            <p class="exp__descr">
              <span class="exp__key">//</span>
              <span class="exp__value"
                >Оставьте заявку и получите консультацию в течение 1 часа</span
              >
            </p>
            <a href="#contacts" class="exp__cta">Написать мне →</a>
          </div>
        </article>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped>
@import './experience.css';
</style>
