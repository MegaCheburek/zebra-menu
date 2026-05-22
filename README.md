# Zebra Coffee Menu Guide

Личный сайт-глоссарий для быстрого изучения меню.

## Запуск

```bash
npm install
npm run dev
```

## Сборка

```bash
npm run build
```

## GitHub Pages

1. Создай репозиторий на GitHub.
2. В package.json замени homepage на свою ссылку, например:

```json
"homepage": "https://your-name.github.io/zebra-menu"
```

3. Выполни:

```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/your-name/zebra-menu.git
git push -u origin main
npm run deploy
```
