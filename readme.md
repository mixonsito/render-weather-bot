# Telegram Weather Bot

Простой Telegram бот-синоптик.  
Функции:
- Выдаёт прогноз по запросу `/forecast`
- Настройка координат `/setcoords`
- Назначение админа `/setadmin`
- Помощь `/help`

## Деплой на Render Free
1. Создайте Web Service на Render с Python.
2. Установите переменные окружения:
   - `TELEGRAM_TOKEN` — токен бота
3. Build Command: `pip install -r requirements.txt`
4. Start Command: `python main.py`
