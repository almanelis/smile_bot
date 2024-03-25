# Бот с котиками и собачками для поднятия настроения
## Как запустить
1. Клонируем репозиторий
```
git clone git@github.com:almanelis/smile_bot.git
```
2. Создаём, активируем виртуальное окружение, устанавливаем зависимости
```
python -m venv venv
```
```
source venv/Scripts/activate
```
```
pip install -r requirements.txt
```
3. Вставляем токен бота в переменную TELEGRAM_TOKEN:
```
TELEGRAM_TOKEN = <ваш токен>
```
4. Запускаем бота
```
python kittybot.py
```
## Наслаждаемся 😍🥰