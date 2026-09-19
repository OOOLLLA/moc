# МОС — офлайн калькулятор

Готово для GitHub Pages.

## Как запустить

1. Создай новый репозиторий на GitHub, например `moc`.
2. Загрузи все файлы из этой папки В КОРЕНЬ репозитория:
   - `index.html`
   - `sw.js`
   - `manifest.webmanifest`
   - `icon-192.png`
   - `icon-512.png`
   - `.nojekyll`
3. Открой:
   `Settings → Pages`
4. В `Build and deployment` выбери:
   `Deploy from a branch`
5. Branch: `main`, folder: `/ (root)`.
6. Нажми Save.

Через несколько минут GitHub выдаст адрес вида:

`https://USERNAME.github.io/moc/`

Открой его на iPhone именно в Safari.

Затем:
`Поделиться → На экран «Домой»`.

После первого открытия приложение сможет работать офлайн благодаря service worker.
