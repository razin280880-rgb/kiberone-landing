# KIBERone — общий лендинг

Лендинг сети KIBERone (7 городов: Челны, Нижнекамск, Казань, Елабуга, Краснодар, Сургут, Пермь).

- **Стек:** чистый HTML5 + embedded CSS + vanilla JS. Без сборки.
- **Шрифт:** Inter (Google Fonts).
- **Виджет:** подключён AI-ассистент Камилла с прод-бэка `assistant.it-kiber.ru`.
- **Деплой:** Cloudflare Pages → custom domain `start.it-kiber.ru`.

## Файлы

- `index.html` — основной лендинг (актуальный)
- `index-b.html`, `index-c.html` — старые варианты копирайта (на сравнение)
- `index-5000.html` — лендинг под все каналы оффера «5 000 ₽ на кибер-баланс» (листовка, автообзвон Елабуги, реактивация, школьные каналы)
- `logo-kiberone*.png`, `favicon.png` — брендовые ассеты

## Локальный запуск

```bash
python -m http.server 8080
# открыть http://localhost:8080
```

## Деплой

Автодеплой из этого репозитория через Cloudflare Pages. Push в `main` → CF Pages пересобирает за 30-60 сек.

CI подключён 2026-06-27.
