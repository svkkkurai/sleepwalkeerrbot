# ¿ локи〡предложка бот

❤ Спасибо за поддержку нашего сообщества!</br>ℹ️Ниже инструкция о том, как настроить бота для своего паблика.

## 🎯 Список изменений
**♿Версия: 1.06**
- Перенесли функцию bot_info в другое место, чтобы просто так не засорять KeyboardMarkup;
- В bot_info теперь присутствует **Список изменений**;
- Обновили зависимости - теперь устанавливается всё сразу... Наверное!
- Добавлены файлы `bot_run.sh (UNIX)` и `bot_run.bat (Windows NT)` для быстрого запуска в системе (например, кинуть в автозагрузку!).


## 🛠️ Установка
1. Сперва скопируйте репозиторий в вашу рабочую директорию: 
```git clone https://github.com/svkkkurai/sleepwalkeerrbot.git```
2. Перейдите в рабочую директорию:
```cd sleepwalkeerrbot```.
3. Установите зависимости: ```pip install -r requirements.txt```.
4. Заполните все поля с ID в файле `config.py`. За что отвечают ID читайте [здесь](#-за-что-отвечают).
5. Запустите `main.py`, после этого будет создана база данных —  `bot_db.sqlite`.
6. Готово!

## 👤 Идентификаторы
### ❓ Как узнать?
❗ Узнать ID вашего чата или канала можно через ботов или сторонний Telegram клиент, кроме TDesktop - здесь можно узнать на ванильном клиенте. Чтобы сделать это, перейдите в **`Настройки → Расширенные → Экспериментальные настройки`** и включите **`Show Peer IDs in Profile`**. После этого в профилях каналов и пользователей будут отображаться ID, которые нам и нужны.

### 💢 За что отвечают?
+ **`TOKEN`** — ваш токен бота, полученный через [BotFather](https://t.me/BotFather);
+ **`CHANNEL_ID`** — ID канала, куда бот будет отправлять посты;
+ **`MODER_CHAT_ID`** — ID чата, куда будут приходить посты на проверку;
+ **`ADMIN_ID`** — ID всех админов (необязательно);
+ **`SENIOR_ADMIN`** — ID админа (подразумевается, что ваш). Имеет расширенные права, например, завершение работы сервера.

## ✨Заключение
😎 Поздравляю, бот работает! Осталось перевести его на хостинг, ну это такое... Дело за малым.</br></br>💢Предложения или замечания? Напишите [sakkkurai](https://t.me/lksakurai) в Telegram!