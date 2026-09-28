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
    - **Performance: 30** 
    - **Accessibility: 84** 
    - **Best Practices: 77** 
    - **SEO: 92** 

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
