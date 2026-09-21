# Isuna — статический сайт

Один самодостаточный файл: `index.html` (весь код, шрифты, иллюстрации и логотипы внутри).

## Деплой на Vercel через GitHub

1. Создайте репозиторий на GitHub и загрузите в его корень содержимое этой папки (`index.html`, `vercel.json`, этот README).
2. На vercel.com → **Add New… → Project** → импортируйте репозиторий.
3. Framework Preset: **Other**. Build Command и Install Command оставьте пустыми, Output Directory: `.` (корень).
4. **Deploy**. Vercel отдаст `index.html` как статическую страницу.

Обновление: коммит в основную ветку — Vercel пересоберёт автоматически.
