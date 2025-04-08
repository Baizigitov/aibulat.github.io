# Telegram GPT Chat Bot 🤖

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://python.org)
[![Telegram](https://img.shields.io/badge/Telegram-Bot-blue)](https://core.telegram.org/bots)
[![OpenAI](https://img.shields.io/badge/OpenAI-GPT_3.5-green)](https://openai.com)

Телеграм-бот, использующий OpenAI GPT-3.5 Turbo для генерации ответов на вопросы пользователей.

## 🚀 Особенности
- Ответы на текстовые вопросы
- Обработка ошибок API
- Логирование запросов
- Простая интеграция с Telegram

## ⚙️ Требования
- Python 3.8+
- Аккаунт OpenAI с API-ключом
- Telegram Bot Token от [@BotFather](https://t.me/BotFather)

## 📦 Установка
1. Клонируйте репозиторий:
```bash
git clone https://github.com/ваш-username/telegram-gpt-bot.git
cd telegram-gpt-bot
Установите зависимости:

bash
Copy
pip install -r requirements.txt
🔧 Настройка
Создайте файл .env в корне проекта:

env
Copy
TELEGRAM_BOT_TOKEN=ваш_telegram_токен
OPENAI_API_KEY=ваш_openai_ключ
Получите токены:

Telegram Bot Token: через @BotFather

OpenAI API Key: в личном кабинете OpenAI

🖥️ Запуск
bash
Copy
python bot.py
🎮 Использование
Начните диалог командой /start

Задавайте любые вопросы текстом

Бот ответит используя GPT-3.5 Turbo

Пример диалога:

Copy
Пользователь: Напиши рецепт борща
Бот: 1. Приготовьте бульон из говядины...
📝 Структура проекта
Copy
telegram-gpt-bot/
├── bot.py            # Основной код бота
├── requirements.txt  # Зависимости
└── .env.example      # Шаблон файла конфигурации
🔄 Команды
/start - начать диалог

Любой текст - получить ответ от ИИ

⚠️ Ограничения
Максимальная длина ответа: 4096 символов (ограничение Telegram)

Скорость ответа зависит от OpenAI API

Требуется стабильное интернет-соединение

🌟 Возможные улучшения
Добавить обработку изображений

Реализовать кэширование запросов

Добавить систему контекста диалога

Настроить rate limiting

📄 Лицензия
MIT License. Подробнее в файле LICENSE.
