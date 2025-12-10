# Web Layout Project (SCSS)

Проект представляет собой практическую работу по созданию веб-макета с использованием современных технологий вёрстки и препроцессора SCSS.

## 📁 Структура проекта
```
src/
├── scss/ # Исходные SCSS-файлы
│ ├── vendor/
│ │ └── _normalize.scss
│ ├── components/
│ │ ├── _cards.scss
│ │ ├── _catalogue.scss
│ │ ├── _footer.scss
│ │ ├── _form.scss
│ │ ├── _header.scss
│ │ ├── _product.scss
│ │ └── _ui.scss
│ ├── mixins/
│ │ ├── _breakpoint.scss
│ │ ├── _burger.scss
│ │ ├── _checkbox.scss
│ │ ├── _disable-mob-hover.scss
│ │ ├── _flex.scss
│ │ ├── _font-face.scss
│ │ ├── _layout.scss
│ │ ├── _mini.scss
│ │ └── _tabs.scss
│ ├── _fonts.scss
│ ├── _mixixns.scss
│ ├── _settings.scss
│ ├── _vars.scss
│ ├── vendor.scss
│ └── main.scss # Основной файл для импорта всех стилей
├── js/ # Скрипты (например, burger-menu.js)
├── imag/ # Изображения для проекта
├── partials/ # Разметка компонентов
├── resourses/
│ ├── fonts/ # Шрифты
│ └── favicon.svg
├── index.html # Главная страница
├── catalogue.html
└── product.html
```
## 🛠 Технологии

- **HTML5** — семантическая разметка
- **SCSS/SASS** — препроцессор для стилей (модульная структура, переменные, миксины)
- **CSS3** — Flexbox/Grid для адаптивной вёрстки
- **JavaScript** — интерактивные элементы (бургер-меню)
- **Git** — контроль версий


## 🚀 Как запустить проект локально

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/sh-anastasia06/weblayout-scss.git
2. Перейдите в папку проекта:
   ```bash
   cd weblayout-scss
3. Откройте файл index.html в браузере или используйте Live Server в VS Code.

## 🎯 Основные особенности

- Модульная архитектура SCSS (разделение на base, components, layout, pages)
- Адаптивный дизайн (поддержка мобильных устройств)
- Использование CSS-переменных для цветов и шрифтов
- Семантические теги HTML5
- Интерактивное бургер-меню для мобильной навигации
- Сброс стандартных стилей (_reset.scss)

## 📄 Лицензия

Проект создан в учебных целях. Код доступен для ознакомления и использования.
