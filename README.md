# Сборка Webpack 5.5

Простенькая сборка Webpack 5.5 по видео Саши Репеты для нашего уровня студентов, но РАБОЧАЯ!

## Для установки сборки:

1. Копируем этот репозиторий себе.
2. Открываем в VSCode и запускаем в консоли команду `npm ci` чтобы установить загрузчики и плагины из перечня
   "package-lock.json".
3. Меняем под себя значения ключей в файле "package.json":
   1. `"name": "webpack-5.5-lite"` на `"name": "имя_вашего_проекта"` или просто `"name": ""`;
   2. В параметрах "repository" - `"url": "git+https://github.com/Eduard-Konovka/webpack-5.5-lite.git"` на
      `"url": "git+https://github.com/ваше_имя_на_ГитХабе/имя_вашего_проекта.git"`;
   3. В параметрах "bugs" - `"url": "https://github.com/Eduard-Konovka/webpack-5.5-lite.git/issues"` на
      `"url": "https://github.com/ваше_имя_на_ГитХабе/имя_вашего_проекта.git/issues"`;
   4. `"author": "Eduard Konovka <ed098ua@gmail.com>"` на `"author": "Ваше_имя <ваш_e-mail>"` или просто `"author": ""`;
   5. `"homepage": "https://Eduard-Konovka.github.io/webpack-5.5-lite"` на
      `"homepage": "https://ваше_имя_на_ГитХабе.github.io/имя_вашего_проекта"`.

## Команды скриптов в консоли bash:

1. `npm start` - для запуска разработки и автоматического запуска DevServer.
2. `npm run dev` - для запуска разработки и создания в папке build файлов разработки (index.html, main.css, main.js,
   изображения и др.).
3. `npm run prod` - для запуска продакшена и создания в папке build минифицированных файлов продакшена (index.html,
   main.css, main.js, изображения и др.).
4. `npm run deploy` - для деплоя файлов разработки на ГитХаб.
