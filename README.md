# NOVIX — лендинг магазина AirPods

Статический сайт без сборки и зависимостей: HTML, CSS и JavaScript в одном файле `index.html`.

## Структура
- `index.html` — вся страница; настройки в блоке `НАСТРОЙКИ САЙТА` в начале `<script>`
- `img/` — фотографии товаров (пути указаны в `MODELS` и `HERO_IMAGE`)
- `favicon.svg` — иконка вкладки
- `vercel.json` — настройки Vercel (кэш картинок)

## Что где менять (блок настроек в `index.html`)
- `ORDER_URL` — ссылка всех кнопок «Заказать»
- `MODELS` — названия, описания и фото моделей
- `PRICES` — цены (один объект)
- `ADVANTAGES` — карточки «Почему NOVIX»
- `REVIEWS` — отзывы и оценки

## Локальный просмотр
`python3 -m http.server 8000` в папке проекта, затем http://localhost:8000

## Публикация на Vercel
Импортируйте репозиторий на vercel.com, Framework Preset — Other, Build Command и Output Directory оставьте пустыми.
