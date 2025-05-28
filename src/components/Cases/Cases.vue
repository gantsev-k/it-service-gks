<template>
  <section class="cases" id="cases" aria-labelledby="cases-title">
    <div class="container">
      <!-- <h2 class="cases__title">> кейсы.загрузить(<span class="arg">решено: true</span>)</h2> -->
      <h2 class="cases__title">Решенные кейсы <span class="code-style">> load_cases()</span></h2>
      <div class="cases__list">
        <article class="case">
          <div class="case__header">
            <span class="case__comment">// Кейс 01: перегрев ноутбука</span>
            <h3 class="case__name">
              Ремонт перегрева <span class="code-style">laptop.revive()</span>
            </h3>
          </div>
          <div class="case__image">
            <img src="./src/img/kitty.jpg" alt="Чистка системы охлаждения ноутбука" />
          </div>
          <p class="case__descr">
            Вентилятор кричал как проклятый. Почистили, заменили термопасту — теперь шепчет, как
            новый.
          </p>
        </article>

        <article class="case">
          <div class="case__header">
            <span class="case__comment">// Кейс 02: скрытые вирусы</span>
            <h3 class="case__name">
              Удаление вирусов <span class="code-style">virus.scan()</span>
            </h3>
          </div>
          <div class="case__image">
            <img src="./src/img/pc.png" alt="Удаление вредоносного ПО" />
          </div>
          <p class="case__descr">
            Нашли скрытое вредоносное ПО. Вылечили систему без переустановки Windows.
          </p>
        </article>

        <article class="case">
          <div class="case__header">
            <span class="case__comment">// Кейс 03: спасение данных</span>
            <h3 class="case__name">
              Восстановление HDD <span class="code-style">hdd.resurrect()</span>
            </h3>
          </div>
          <div class="case__image">
            <img src="./src/img/hdd.jpg" alt="Восстановление данных с жесткого диска" />
          </div>
          <p class="case__descr">
            HDD издавал «клик смерти». Восстановили 98% данных. Клиент получил рекомендацию по
            переходу на SSD.
          </p>
        </article>

        <article class="case">
          <div class="case__header">
            <span class="case__comment">// Кейс 04: синий экран</span>
            <h3 class="case__name">
              Исправление BSOD <span class="code-style">windows.fix()</span>
            </h3>
          </div>
          <div class="case__image">
            <img src="./src/img/pc.png" alt="Исправление синего экрана смерти" />
          </div>
          <p class="case__descr">
            Синий экран появлялся каждые 2 часа. Обнаружили конфликт драйверов — система работает
            стабильно 3+ месяца.
          </p>
        </article>

        <article class="case">
          <div class="case__header">
            <span class="case__comment">// Кейс 05: медленная загрузка</span>
            <h3 class="case__name">
              Ускорение Windows <span class="code-style">system.optimize()</span>
            </h3>
          </div>
          <div class="case__image">
            <img src="./src/img/win-setup.jpg" alt="Оптимизация Windows" />
          </div>
          <p class="case__descr">
            Загрузка системы занимала 4+ минуты. Отключили 57 фоновых процессов — теперь загружается
            за 60 секунд.
          </p>
        </article>

        <article class="case">
          <div class="case__header">
            <span class="case__comment">// Кейс 06: Проблемы с Wi-Fi</span>
            <h3 class="case__name">
              Ремонт Wi-Fi подключения <span class="code-style">wifi.fix()</span>
            </h3>
          </div>
          <div class="case__image">
            <img src="./src/img/wifi.jpg" alt="Настройка Wi-Fi подключения" />
          </div>
          <p class="case__descr">
            Wi-Fi постоянно отключался каждые 10 минут. Обнаружил конфликт IP-адресов в сети -
            настроил статические адреса и обновил драйвер адаптера. Теперь соединение стабильное уже
            2 месяца.
          </p>
        </article>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped>
@import './cases.css';
</style>
