# Технический аудит конкурентов

## 1. Goodreads

**Адрес ресурса:** https://www.goodreads.com

### 1.1. Анализ архитектуры и технологического стека
- **Основные технологии: JS-фреймворк: Twitter Flight, React, Prototype; Веб-фреймворк: Ruby on Rails** 
- **API и запросы: OpenQL**
- **Сторонние сервисы: Рекламная сеть: Google Publisher Tag, DoubleClick Floodlight, Amazon Advertising, Twitter Ads; Производительность: Priority Hints, LazySizes**

### 1.2. Семантические элементы HTML5
- **Найдены теги: `<header>`, `<nav>`, `<main>`, `<article>`, `<section>` и т.д.**
- **Примеры семантических классов (для div-вёрстки): `<div class="Header__contents">`, `<div class="Spotlight">`, `<div class="Ad Ad__topBanner">` и т.д.**

### 1.3. Адаптивность
- **Наличие Media Queries: Да**
- **Примеры: @media only screen and (max-width: 39.9375em) {
    :root {
        --num-left-col: 0;
        --num-right-col: 2;
    }
}**

### 1.4. Анализ с помощью Lighthouse
- **Условия проверки: Ноутбук, домашний WiFi, дома**
- **Результаты:**
    - **Performance: 30
    1)First Contentful Paint: 6,5 сек.
    Первая отрисовка контента – показатель, который отражает время между началом загрузки страницы и появлением первого изображения или блока текста.
    2)Largest Contentful Paint: 9,0 сек.
    Отрисовка самого крупного контента – показатель, который отражает время, требуемое на полную отрисовку самого крупного изображения или текстового блока. 
    3)Total Blocking Time: 2 240 мс
    Сумма (в миллисекундах) всех периодов от первой отрисовки контента до загрузки для взаимодействия, когда скорость выполнения задач превышала 50 мс.
    4)Cumulative Layout Shift: 0,043
    Совокупное смещение макета – это величина, на которую смещаются видимые элементы области просмотра при загрузке.
    5)Speed Index: 8,9 сек.
    Speed Index отражает, как быстро на странице появляется контент.** 
    - **Accessibility: 84 (Специальные возможности)
    1)Названия и ярлыки
    2)ARIA
    3)Таблицы и списки** 
    - **Best Practices: 77 (Рекомендации)
    1)Ошибки и сторонние файлы cookie
    2)Надежность и безопасность
    3)Совместимость с браузерами** 
    - **SEO: 92
    Эти проверки позволяют узнать, соответствует ли страница основным рекомендациям к поисковой оптимизации.** 

### 1.5. Локальное хранилище и Cookies
- **Local Storage** 
- **Session Storage** 
- **Cookies** 

---

## 2. Letterboxd
**Адрес ресурса:** https://letterboxd.com

### 1.1. Анализ архитектуры и технологического стека
- **Основные технологии: JS-фреймворк: GSAP, React; Веб-фреймворк: Nette Framework** 
- **API и запросы: REST API**
- **Сторонние сервисы: Рекламная сеть: 33Across, Amazon Advertising; Производительность: Priority Hints; Аналитика: Google Analytics**

### 1.2. Семантические элементы HTML5
- **Найдены теги: `<header>`, `<nav>`, `<main>`, `<article>`, `<section>` и т.д.**
- **Примеры семантических классов (для div-вёрстки): `<div class="backdrop-container">`, `<div class="backdrop-container">`, `<div class="backdropimage js-backdrop-image">` и т.д.**

### 1.3. Адаптивность
- **Наличие Media Queries: Нет**

### 1.4. Анализ с помощью Lighthouse
- **Условия проверки: Ноутбук, домашний WiFi, дома**
- **Результаты:**
    - **Performance: 27** 
    - **Accessibility: 90** 
    - **Best Practices: 50** 
    - **SEO: 92** 

### 1.5. Локальное хранилище и Cookies
- **Local Storage** 
- **Session Storage** 
- **Cookies** 

---

## 3. Daylio
**Адрес ресурса:** https://daylio.net

### 1.1. Анализ архитектуры и технологического стека
- **Основные технологии: Язык программирования: PHP; JS-библиотека: Swiper, jQuery UI** 
- **API и запросы: Daylio нет официального публичного API. Разработчики позиционируют его как полностью приватный офлайн-дневник, поэтому все данные хранятся локально на вашем устройстве.**
- **Сторонние сервисы: Аналитика Site Kit; Производительность: Priority Hints, WP Fastest Cache**

### 1.2. Семантические элементы HTML5
- **Найдены теги:  `<nav>`, `<main>`, `<article>`, `<section>` и т.д.**
- **Примеры семантических классов (для div-вёрстки): `<div class="cmplz-header">`, `<div class="cmplz-title">`, `<div class="cmplz-buttons">` и т.д.**

### 1.3. Адаптивность
- **Наличие Media Queries: Да**
- **Примеры: @media (max-width: 1024px) {
    .elementor-kit-9 {
        font-size: 18px;
    }
}**

### 1.4. Анализ с помощью Lighthouse
- **Условия проверки: Ноутбук, домашний WiFi, дома**
- **Результаты:**
    - **Performance: 79** 
    - **Accessibility: 91** 
    - **Best Practices: 96** 
    - **SEO: 85** 

### 1.5. Локальное хранилище и Cookies
- **Local Storage** 
- **Session Storage** 
- **Cookies** 
