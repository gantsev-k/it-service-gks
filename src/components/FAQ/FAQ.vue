<template>
  <section class="faq" id="faq">
    <div class="container">
      <h2 class="faq__title">
        Частые вопросы > faq.load(<span class="arg">items: <span id="faqCount">0</span></span
        >)<span class="blinking-cursor">_</span>
      </h2>

      <div class="accordion">
        <!-- Категория 1 -->
        <h3 class="faq-category">Основные проблемы</h3>

        <div class="accordion__item">
          <button class="accordion__header">
            <span class="accordion__question">Почему компьютер тормозит?</span>
            <svg class="accordion__icon" width="16" height="16" viewBox="0 0 24 24">
              <path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z" />
            </svg>
          </button>
          <div class="accordion__content">
            <div class="code-style">
              <p><strong>Основные причины:</strong></p>
              <p>- Перегружена оперативная память</p>
              <p>- Много программ в автозагрузке</p>
              <p>- Перегрев компонентов</p>
              <p>- Вирусы или вредоносное ПО</p>
              <p class="solution-cta">
                <strong>Решение:</strong> Диагностика + чистка системы (1-2 часа)
              </p>
            </div>
          </div>
        </div>

        <div class="accordion__item">
          <button class="accordion__header">
            <span class="accordion__question">Что делать, если компьютер не включается?</span>
            <svg class="accordion__icon" width="16" height="16" viewBox="0 0 24 24">
              <path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z" />
            </svg>
          </button>
          <div class="accordion__content">
            <div class="code-style">
              <p><strong>Что проверить:</strong></p>
              <p>- Подключение к розетке</p>
              <p>- Кнопку питания на блоке</p>
              <p>- Индикаторы на материнской плате</p>
              <p>- Звуковые сигналы при включении</p>
              <p class="solution-cta">
                <strong>Решение:</strong> Аппаратная диагностика (от 30 минут)
              </p>
            </div>
          </div>
        </div>

        <div class="accordion__item">
          <button class="accordion__header">
            <span class="accordion__question">Почему появляется синий экран?</span>
            <svg class="accordion__icon" width="16" height="16" viewBox="0 0 24 24">
              <path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z" />
            </svg>
          </button>
          <div class="accordion__content">
            <div class="code-style">
              <p><strong>Возможные причины:</strong></p>
              <p>- Проблемы с драйверами (65% случаев)</p>
              <p>- Ошибки оперативной памяти</p>
              <p>- Перегрев компонентов</p>
              <p>- Повреждение системных файлов</p>
              <p class="solution-cta">
                <strong>Решение:</strong> Анализ дампа памяти + исправление
              </p>
            </div>
          </div>
        </div>

        <!-- Категория 2 -->
        <h3 class="faq-category">Обслуживание и апгрейд</h3>

        <div class="accordion__item">
          <button class="accordion__header">
            <span class="accordion__question">Как часто нужно чистить компьютер?</span>
            <svg class="accordion__icon" width="16" height="16" viewBox="0 0 24 24">
              <path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z" />
            </svg>
          </button>
          <div class="accordion__content">
            <div class="code-style">
              <p><strong>Рекомендации:</strong></p>
              <p>- Стационарный ПК: раз в 1-2 года</p>
              <p>- Ноутбук: раз в 1-1.5 года</p>
              <p>- В пыльных помещениях: каждые 6 месяцев</p>
              <p>- Серверы: каждые 3-6 месяцев</p>
              <p class="solution-cta">
                <strong>Решение:</strong> Комплексная чистка с заменой термопасты
              </p>
            </div>
          </div>
        </div>

        <div class="accordion__item">
          <button class="accordion__header">
            <span class="accordion__question">SSD или HDD - что лучше?</span>
            <svg class="accordion__icon" width="16" height="16" viewBox="0 0 24 24">
              <path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z" />
            </svg>
          </button>
          <div class="accordion__content">
            <div class="code-style">
              <p><strong>Сравнение:</strong></p>
              <p>- SSD: в 5-10 раз быстрее, бесшумный, надежнее</p>
              <p>- HDD: дешевле за объем, подходит для архива</p>
              <p>- Срок службы: современные SSD работают 5-7+ лет</p>
              <p class="solution-cta">
                <strong>Решение:</strong> Подберу оптимальный вариант под ваш бюджет
              </p>
            </div>
          </div>
        </div>

        <div class="accordion__item">
          <button class="accordion__header">
            <span class="accordion__question">Как ускорить старый компьютер?</span>
            <svg class="accordion__icon" width="16" height="16" viewBox="0 0 24 24">
              <path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z" />
            </svg>
          </button>
          <div class="accordion__content">
            <div class="code-style">
              <p><strong>Эффективные методы:</strong></p>
              <p>1. Установка SSD (+150% скорости)</p>
              <p>2. Добавление оперативной памяти</p>
              <p>3. Чистая установка Windows</p>
              <p>4. Оптимизация системы</p>
              <p class="solution-cta"><strong>Решение:</strong> Комплексный апгрейд за 2-3 часа</p>
            </div>
          </div>
        </div>

        <!-- Категория 3 -->
        <h3 class="faq-category">Безопасность и данные</h3>

        <div class="accordion__item">
          <button class="accordion__header">
            <span class="accordion__question">Как защититься от вирусов?</span>
            <svg class="accordion__icon" width="16" height="16" viewBox="0 0 24 24">
              <path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z" />
            </svg>
          </button>
          <div class="accordion__content">
            <div class="code-style">
              <p><strong>Базовые правила:</strong></p>
              <p>- Установите антивирус (бесплатные варианты есть)</p>
              <p>- Регулярно обновляйте Windows</p>
              <p>- Не открывайте подозрительные письма</p>
              <p>- Используйте блокировщик рекламы</p>
              <p class="solution-cta">
                <strong>Решение:</strong> Настрою комплексную защиту за 1 час
              </p>
            </div>
          </div>
        </div>

        <div class="accordion__item">
          <button class="accordion__header">
            <span class="accordion__question">Как восстановить удаленные файлы?</span>
            <svg class="accordion__icon" width="16" height="16" viewBox="0 0 24 24">
              <path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z" />
            </svg>
          </button>
          <div class="accordion__content">
            <div class="code-style">
              <p><strong>Важно:</strong></p>
              <p>- Не записывайте новые данные на диск</p>
              <p>- Не устанавливайте программы на тот же диск</p>
              <p>- Шансы восстановления: 70-90% для HDD, 30-50% для SSD</p>
              <p class="solution-cta">
                <strong>Решение:</strong> Профессиональное восстановление данных
              </p>
            </div>
          </div>
        </div>

        <div class="accordion__item">
          <button class="accordion__header">
            <span class="accordion__question">Как сделать резервную копию?</span>
            <svg class="accordion__icon" width="16" height="16" viewBox="0 0 24 24">
              <path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z" />
            </svg>
          </button>
          <div class="accordion__content">
            <div class="code-style">
              <p><strong>Варианты резервного копирования:</strong></p>
              <p>- Внешний жесткий диск (самый простой)</p>
              <p>- Облачные хранилища (Google Drive, Яндекс.Диск)</p>
              <p>- Специализированные программы (Acronis, Macrium)</p>
              <p class="solution-cta">
                <strong>Решение:</strong> Настрою автоматическое резервное копирование
              </p>
            </div>
          </div>
        </div>

        <!-- Категория 4 -->
        <h3 class="faq-category">Сеть и интернет</h3>

        <div class="accordion__item">
          <button class="accordion__header">
            <span class="accordion__question">Почему Wi-Fi плохо работает?</span>
            <svg class="accordion__icon" width="16" height="16" viewBox="0 0 24 24">
              <path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z" />
            </svg>
          </button>
          <div class="accordion__content">
            <div class="code-style">
              <p><strong>Основные причины:</strong></p>
              <p>- Перегружен канал Wi-Fi (соседние сети)</p>
              <p>- Физические препятствия (стены, мебель)</p>
              <p>- Устаревший роутер</p>
              <p>- Проблемы с драйверами</p>
              <p class="solution-cta">
                <strong>Решение:</strong> Настройка Wi-Fi и выбор оптимального канала
              </p>
            </div>
          </div>
        </div>

        <div class="accordion__item">
          <button class="accordion__header">
            <span class="accordion__question">Как защитить домашнюю сеть?</span>
            <svg class="accordion__icon" width="16" height="16" viewBox="0 0 24 24">
              <path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z" />
            </svg>
          </button>
          <div class="accordion__content">
            <div class="code-style">
              <p><strong>Меры защиты:</strong></p>
              <p>- Сменить пароль от роутера</p>
              <p>- Включить шифрование WPA2/WPA3</p>
              <p>- Отключить WPS</p>
              <p>- Обновить прошивку роутера</p>
              <p class="solution-cta">
                <strong>Решение:</strong> Полная настройка безопасности сети
              </p>
            </div>
          </div>
        </div>

        <!-- Категория 5 -->
        <h3 class="faq-category">Программы и ОС</h3>

        <div class="accordion__item">
          <button class="accordion__header">
            <span class="accordion__question">Какую версию Windows выбрать?</span>
            <svg class="accordion__icon" width="16" height="16" viewBox="0 0 24 24">
              <path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z" />
            </svg>
          </button>
          <div class="accordion__content">
            <div class="code-style">
              <p><strong>Рекомендации:</strong></p>
              <p>- Новые компьютеры: Windows 11</p>
              <p>- Компьютеры 5-7 лет: Windows 10</p>
              <p>- Очень старые ПК: Windows 8.1 или Linux</p>
              <p>- Для офиса: Windows 10 LTSC</p>
              <p class="solution-cta">
                <strong>Решение:</strong> Помогу выбрать и установить оптимальную версию
              </p>
            </div>
          </div>
        </div>

        <div class="accordion__item">
          <button class="accordion__header">
            <span class="accordion__question">Нужен ли антивирус для Windows 10/11?</span>
            <svg class="accordion__icon" width="16" height="16" viewBox="0 0 24 24">
              <path d="M19 13h-6v6h-2v-6H5v-2h6V5h2v6h6v2z" />
            </svg>
          </button>
          <div class="accordion__content">
            <div class="code-style">
              <p><strong>Защита Windows:</strong></p>
              <p>- Встроенный Защитник Windows - базовый уровень</p>
              <p>- Для полной защиты лучше сторонний антивирус</p>
              <p>- Бесплатные варианты: Kaspersky Free, Avast Free</p>
              <p class="solution-cta">
                <strong>Решение:</strong> Установлю и настрою антивирусную защиту
              </p>
            </div>
          </div>
        </div>
      </div>

      <!-- Кнопка "Задать вопрос" -->
      <div class="faq-cta">
        <p>Не нашли ответ на свой вопрос?</p>
        <a href="#feedback_form" class="cta-button">Задать вопрос</a>
      </div>
    </div>
  </section>
</template>

<script setup lang="ts"></script>

<style scoped>
@import './faq.css';
</style>
