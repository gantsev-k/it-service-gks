<template>
  <section class="contacts" id="contacts">
    <div class="container">
      <h2 class="contacts__title">
        Свяжитесь со мной <span class="code-style">> contacts.now()</span>
      </h2>

      <div class="contacts__container">
        <!-- Телефон -->
        <div class="contact__item">
          <div class="contact__header">
            <span class="contact__comment">// Самый быстрый способ</span>
            <h3 class="contact__name">Телефон <span class="code-style">> call</span></h3>
          </div>
          <a href="tel:+79931074700" class="contact__value">+7 (993) 107-47-00</a>
          <p class="contact__hours">с 9:00 до 21:00 без выходных</p>
        </div>

        <!-- Email -->
        <div class="contact__item">
          <div class="contact__header">
            <span class="contact__comment">// Для сложных вопросов</span>
            <h3 class="contact__name">Email <span class="code-style">> mail</span></h3>
          </div>
          <a href="mailto:gantsev.k.service@gmail.com" class="contact__value"
            >gantsev.k.service@gmail.com</a
          >
          <p class="contact__note">Ответ в течение 2 часов</p>
        </div>

        <!-- Мессенджеры -->
        <div class="contact__item">
          <div class="contact__header">
            <span class="contact__comment">// Онлайн-консультация</span>
            <h3 class="contact__name">Мессенджеры <span class="code-style">> chat</span></h3>
          </div>
          <div class="contact__messengers">
            <a href="https://t.me/gantsev_k" class="contact__link">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-telegram"
                viewBox="0 0 16 16"
              >
                <path
                  d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0M8.287 5.906q-1.168.486-4.666 2.01-.567.225-.595.442c-.03.243.275.339.69.47l.175.055c.408.133.958.288 1.243.294q.39.01.868-.32 3.269-2.206 3.374-2.23c.05-.012.12-.026.166.016s.042.12.037.141c-.03.129-1.227 1.241-1.846 1.817-.193.18-.33.307-.358.336a8 8 0 0 1-.188.186c-.38.366-.664.64.015 1.088.327.216.589.393.85.571.284.194.568.387.936.629q.14.092.27.187c.331.236.63.448.997.414.214-.02.435-.22.547-.82.265-1.417.786-4.486.906-5.751a1.4 1.4 0 0 0-.013-.315.34.34 0 0 0-.114-.217.53.53 0 0 0-.31-.093c-.3.005-.763.166-2.984 1.09"
                />
              </svg>
              @gantsev_k
            </a>
          </div>
        </div>

        <!-- Адрес -->
        <div class="contact__item">
          <div class="contact__header">
            <span class="contact__comment">// Для личного визита</span>
            <h3 class="contact__name">Адрес <span class="code-style">> location</span></h3>
          </div>
          <p class="contact__value">г. Екатеринбург</p>
          <p class="contact__note">Точный адрес при согласовании</p>
        </div>
      </div>

      <!-- Форма обратной связи -->
      <div class="contact__form-wrapper" id="feedback_form">
        <div class="contact__form-header">
          <span class="contact__comment">// Быстрая заявка</span>
          <h3 class="contact__name">
            Форма обратной связи <span class="code-style">> feedback_form</span>
          </h3>
        </div>

        <form id="feedbackForm" class="feedback-form">
          <div class="form-group">
            <label for="name" class="form-label">Ваше имя</label>
            <input
              type="text"
              id="name"
              name="name"
              required
              class="form-input"
              placeholder="Как к вам обращаться?"
            />
          </div>

          <div class="form-group">
            <label for="contact" class="form-label">Контакт</label>
            <input
              type="text"
              id="contact"
              name="contact"
              required
              class="form-input"
              placeholder="Телефон или Email"
            />
          </div>

          <div class="form-group">
            <label for="message" class="form-label">Опишите проблему</label>
            <textarea
              id="message"
              name="message"
              required
              class="form-textarea"
              placeholder="Что случилось с вашим устройством?"
            ></textarea>
          </div>

          <button type="submit" class="form-submit">Отправить заявку →</button>
          <div id="formStatus" class="form-status"></div>
        </form>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped>
@import './contacts.css';
</style>
