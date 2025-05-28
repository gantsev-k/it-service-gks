<template>
  <section class="services" id="services">
    <div class="container">
      <h2 class="services__title">Услуги <span class="code-style">> services.list()</span></h2>
      <div class="services__container">
        <article class="service">
          <div class="service__header">
            <span class="service__comment">// Услуга 01</span>
            <h3 class="service__name">
              Удаление вирусов <span class="code-style">deep_clean()</span>
            </h3>
          </div>
          <p class="service__descr">
            Уничтожение вирусов, троянов и рекламного ПО без переустановки системы
          </p>
          <div class="service__price">
            <span class="price__value">2500₽</span>
            <span class="price__note">// гарантия 30 дней</span>
          </div>
        </article>

        <article class="service">
          <div class="service__header">
            <span class="service__comment">// Услуга 02</span>
            <h3 class="service__name">
              Ускорение Windows <span class="code-style">turbo_boost()</span>
            </h3>
          </div>
          <p class="service__descr">
            Чистка от мусора, настройка автозагрузки и оптимизация работы
          </p>
          <div class="service__price">
            <span class="price__value">2000₽</span>
            <span class="price__note">// загрузка в 2 раза быстрее</span>
          </div>
        </article>

        <article class="service">
          <div class="service__header">
            <span class="service__comment">// Услуга 03</span>
            <h3 class="service__name">
              Чистая установка ОС <span class="code-style">os.install()</span>
            </h3>
          </div>
          <p class="service__descr">
            Windows/Linux с драйверами и необходимым софтом (без лишних программ)
          </p>
          <div class="service__price">
            <span class="price__value">3000₽</span>
            <span class="price__note">// только нужные компоненты</span>
          </div>
        </article>

        <article class="service">
          <div class="service__header">
            <span class="service__comment">// Услуга 04</span>
            <h3 class="service__name">
              Восстановление данных <span class="code-style">data.rescue()</span>
            </h3>
          </div>
          <p class="service__descr">
            Спасение файлов с повреждённых HDD/SSD (если диск определяется)
          </p>
          <div class="service__price">
            <span class="price__value">5000₽</span>
            <span class="price__note">// даже в критических случаях</span>
          </div>
        </article>

        <article class="service">
          <div class="service__header">
            <span class="service__comment" lang="en">// Услуга 05</span>
            <h3 class="service__name">Ремонт сети <span class="code-style">net.fix()</span></h3>
          </div>
          <p class="service__descr">Настройка интернета, Wi-Fi, VPN и удалённого доступа</p>
          <div class="service__price">
            <span class="price__value">2500₽</span>
            <span class="price__note">// стабильный Wi-Fi и VPN</span>
          </div>
        </article>

        <article class="service">
          <div class="service__header">
            <span class="service__comment" lang="en">Услуга 06</span>
            <h3 class="service__name">
              Настройка бэкапов <span class="code-style">backup.setup()</span>
            </h3>
          </div>
          <p class="service__descr">
            Организация резервного копирования (облако + локальное хранилище)
          </p>
          <div class="service__price">
            <span class="price__value">3000₽</span>
            <span class="price__note">// спокойный сон гарантирован</span>
          </div>
        </article>

        <article class="service">
          <div class="service__header">
            <span class="service__comment" lang="en">// Услуга 07</span>
            <h3 class="service__name">
              Обновление драйверов <span class="code-style">drivers.update()</span>
            </h3>
          </div>
          <p class="service__descr">Решение проблем с драйверами и синими экранами смерти</p>
          <div class="service__price">
            <span class="price__value">2200₽</span>
            <span class="price__note">// без непонятных ошибок</span>
          </div>
        </article>

        <article class="service">
          <div class="service__header">
            <span class="service__comment" lang="en">// Услуга 08</span>
            <h3 class="service__name">
              Подбор программ <span class="code-style">apps.find()</span>
            </h3>
          </div>
          <p class="service__descr">Подбор бесплатных аналогов платных программ</p>
          <div class="service__price">
            <span class="price__value">1500₽</span>
            <span class="price__note">// сэкономим ваши деньги</span>
          </div>
        </article>

        <article class="service">
          <div class="service__header">
            <span class="service__comment" lang="en">// Услуга 09</span>
            <h3 class="service__name">
              Замена комплектующих <span class="code-style">hardware.upgrade()</span>
            </h3>
          </div>
          <p class="service__descr">
            Профессиональная замена HDD на SSD, добавление оперативной памяти, установка видеокарты
            с тестированием
          </p>
          <div class="service__price">
            <span class="price__value">от 1500₽</span>
            <span class="price__note">// + стоимость комплектующих</span>
          </div>
        </article>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped>
@import './services.css';
</style>
