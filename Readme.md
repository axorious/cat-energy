# Cat Energy (Vite)

Онлайн обзор проекта - https://cat-energy-gules.vercel.app/

Проект адаптивного сайта "Cat Energy", собранный на [Vite](https://vitejs.dev/) с использованием SCSS.

## Структура проекта

Ссылка на первоисточник проекта - https://github.com/axorious/2171115-cat-energy-29

```
vite-project/
├── public/                # Статические файлы (favicon, изображения)
├── src/
│   ├── main.js            # Точка входа JS
│   ├── style.scss         # Главный SCSS-файл
│   ├── fonts/             # Шрифты
│   ├── img/               # Изображения
│   └── sass/              # SCSS-модули и блоки
├── index.html             # Главная страница
├── catalog.html           # Каталог продукции
├── form.html              # Форма подбора программы
├── package.json           # Скрипты и зависимости
└── README.md              # Этот файл
```

## Быстрый старт

1. **Установите зависимости:**

   ```sh
   npm install
   ```

2. **Запустите проект в режиме разработки:**

   ```sh
   npm run dev
   ```

3. **Соберите проект для продакшена:**

   ```sh
   npm run build
   ```

4. **Просмотрите production-сборку:**
   ```sh
   npm run preview
   ```

## Особенности

- Используется [Vite](https://vitejs.dev/) для быстрой разработки и сборки.
- Стили пишутся на SCSS (`src/style.scss` и модули в `src/sass/`).
- Подключение шрифтов и изображений через папки `src/fonts/` и `src/img/`.
- Для работы с SCSS используется пакет [`sass`](https://sass-lang.com/).
- Статические файлы (favicon и др.) лежат в папке `public/`.

## Лицензия
