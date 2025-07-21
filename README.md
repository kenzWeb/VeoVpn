# VeoVPN - V2rayTUN Configuration Redirect

Веб-приложение для автоматического перенаправления VPN конфигураций в приложение V2rayTUN.

## Особенности

- 🚀 Автоматическое открытие V2rayTUN с конфигурацией
- 📱 Поддержка iOS и Android
- 🔄 Резервный вариант с ручным вводом конфигурации
- 💫 Красивый современный интерфейс

## Использование

Откройте ссылку в формате:

```
https://your-netlify-app.netlify.app/?key=YOUR_VPN_CONFIG&platform=ios
```

Где:

- `key` - закодированная VPN конфигурация
- `platform` - платформа (`ios` или `android`)

## Развертывание на Netlify

1. Подключите ваш GitHub репозиторий к Netlify
2. Установите настройки сборки:
   - **Build command**: `npm run build`
   - **Publish directory**: `.`
3. Развернуте проект

## Локальная разработка

```bash
# Установить зависимости
npm install

# Запустить локальный сервер
npm start
```

## Структура проекта

```
.
├── index.html      # Главная страница
├── _redirects      # Настройки перенаправлений Netlify
├── netlify.toml    # Конфигурация Netlify
├── package.json    # Настройки проекта
└── README.md       # Документация
```

## Лицензия

ISC
