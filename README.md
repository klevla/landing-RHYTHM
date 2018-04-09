# Проект Landing page "Thomas Rythm"

### Используемые в проекте технологии 

1. Библиотека JavaScript - jQuery
2. API Google Maps
---

### Плагины 
1. Slick-nav - стилизация мобильного меню
2. Slick - стилизация карусели (слайдера)
3. Scroll to - стилизация скролла (кастомный плагин)
4. Header-scroll - стилизация header при скролле (кастомный плагин)
---

### Шрифты и иконки

1. Font-Awesome - иконочный шрифт 
2. Et-line icons - иконочный шрифт 
3. Google fonts: 
* Dosis Light 300 / Dosis Regular 400
* OpenSans Light 300 / OpenSans Regular 400 
---
### Основные компоненты и классы 

***Компоненты***
1. *Стили для заголовков:*
```
.title
.title.title-white
.title.section-title
.title.section-title-light
```
2. *Стили для текста:*
```
.default-text
blockquote, .blockquote
blockquote span, .blockquote span
```
3. *Стандартные кнопки:*
```
.btn 
.btn.btn-default
.btn.btn-black
.btn.btn-xs
```
3. *Отступы между стандартными блоками:*
```
.default-section
.small-section
```
4.  *Стили для форм:*
```
.form-control
textarea.form-control
.form-control.error
.form-info 
```
5. *Иконки:*
```
.icon
.rhomb-icon
.rhomb-icon.black-icon
.rhomb-icon.transparent-icon 
```
6. *Контейнеры:*
```
.container 
.container-fluid
```

***Классы***
1. *Выравнивание элементов по горизонтали и вертикали:*
```
.text-center 
.text-right
.text-justify
.m-auto
.pull-left
.pull-right
```
2.  *Цвет для фона:*
```
.bg-black 
.bg-grey 
```
**Основные контрольные точки media-запросов**
```
@media (max-width: 1200px) - устройства c разрешением до 1200px
@media (max-width: 991px) - устройства c разрешением до 991px
@media (max-width: 767px) - устройства c разрешением до 767px
@media (max-width: 576px) - мобильные устройства c разрешением до 576px
```
---
### Структура папок

Название папок  | Содержание файла
----------------|----------------------
css             | Стили проекта
fonts           | Шрифты и иконки
js              | Файлы js скриптов  и инициализации
img             | Картинки и лого используемые в проекте
index.hml       | Файл html разметки проекта
guide.html      | Представление Grid и Default компонентов и стилей
---