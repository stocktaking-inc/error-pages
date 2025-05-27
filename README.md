# 🦕 Error Pages

## _Проект страниц ошибок для веб-приложения для системы инвентаризации логистического/торгового микро-предприятия._

## 📚 Описание проекта

Данный проект представляет собой отдельный модуль клиентской части системы, в котором реализованы кастомные страницы ошибок для веб-приложения. Основная цель — предоставить информативные и стилизованные страницы для следующих HTTP-ошибок:

- [404 - Страница не найдена](http://localhost:5500/src/pages/404.html)
  ![download (1)](https://github.com/user-attachments/assets/d26697bc-6076-485d-9747-6f660fbd2267)
- [500 - Внутренняя ошибка сервера](http://localhost:5500/src/pages/500.html)
- [503 - Сервис недоступен](http://localhost:5500/src/pages/503.html)

Проект создан с использованием HTML и CSS для быстрого создания страниц ошибок.

---

## 🛠 Технологии

- HTML
- CSS

---

## 🚀 Быстрый старт

1. Клонировать репозиторий:

   ```bash
   git clone https://github.com/your-username/error-pages.git
   cd error-pages
   ```

2. Установить зависимости:

   ```bash
   npm install

   ```

3. Запустить проект в режиме разработки:

   ```bash
   npm run dev
   ```

## 📂 Структура проекта

```pqsql
error-pages/
├── assets/
│   ├── favicons/
│   └── images/
│       ├── 404.png
│       └── warehouse-bg.png
├── font/
│   ├── IBMPlexMono-Bold.woff
│   ├── IBMPlexMono-Regular.woff
│   └── font.css
├── pages/
│   ├── 404.html
│   ├── 500.html
│   └── 503.html
├── styles/
│   ├── animation.css
│   ├── global.css
│   └── reset.css
├── .editorconfig
├── .gitattributes
├── .gitignore
├── .prettierrc.js
├── CHANGELOG.md
├── lefthook.yml
├── package-lock.json
├── package.json
└── README.md
```

## 📜 Последнее обновление

- Последнее обновление: 27 мая 2025 года
