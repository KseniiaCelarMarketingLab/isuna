# Isuna — статический сайт

Один самодостаточный файл `index.html`: весь код, шрифты, логотипы, иллюстрации, фото статей и тексты статей внутри.

## Деплой на Vercel через GitHub

1. Создайте репозиторий на GitHub и загрузите в его корень три файла: `index.html`, `vercel.json`, `README.md`.
2. vercel.com → Add New… → Project → импортируйте репозиторий.
3. Framework Preset: **Other**. Build Command и Install Command — пусто. Output Directory — `.`
4. Deploy.

Обновления: коммит в основную ветку — Vercel опубликует автоматически.
