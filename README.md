Вот примерный README.md файл для описанного задания:

# Телеграм бот для периодического закрепления сообщений

## Описание

Этот бот позволяет периодически закреплять и откреплять указанное сообщение в Telegram чате. 

Основные возможности:

- Закрепление сообщения с уведомлением участников
- Параллельная работа с множеством чатов
- Работа только с администратором, создавшим токен

## Установка

Для работы бота нужен:

- Python 3.10 и выше
- Библиотека aiogram
- Токен для бота от @BotFather
- Вписанный токен и id админа в файл CONFIG.py

Установка зависимостей:

```
pip install -r requirements.txt 
```

## Использование

1. Добавить бота в чат с правами администратора и правами на закрепление сообщений
2. Выполнить команду /add_pin_message 
## Команды

- /add_pin_message - закрепить сообщение