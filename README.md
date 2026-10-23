# Quartz-сайт «Разлом»

Этот vault настроен для Quartz 5. Все заметки и изображения сайта находятся в `content/`.

## Локальный просмотр

```sh
nvm use 22
npm ci
npm run quartz -- build --serve
```

Сайт откроется на `http://localhost:8080`.

## Публикация

Workflow в `.github/workflows/deploy.yml` собирает сайт при push в `main` и публикует его через GitHub Pages. В настройках репозитория откройте **Settings → Pages** и выберите **GitHub Actions** как источник публикации.
