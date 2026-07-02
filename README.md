# Карта радости — Telegram Mini App

Статический Telegram Mini App из HTML-дашборда.

## Файлы

• `index.html` — готовое приложение

## Что добавлено

• Telegram WebApp SDK
• `tg.ready()` и `tg.expand()`
• адаптация высоты под viewport Telegram
• имя пользователя из Telegram, если доступно
• haptic feedback на действия
• локальное сохранение в `localStorage`
• попытка дублировать данные в Telegram CloudStorage, если доступно

## Как запустить локально

```bash
cd /root/karta_radosti_miniapp
python3 -m http.server 8080
```

Открыть: `http://localhost:8080`

## Как подключить в Telegram

1. Задеплоить папку на HTTPS-хостинг: Vercel, Netlify, GitHub Pages, Timeweb.
2. В BotFather открыть своего бота.
3. `Bot Settings` → `Menu Button` или `/newapp`.
4. Указать HTTPS URL приложения.
