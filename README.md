# ¿ локи〡предложка бот

❤ Спасибо за поддержку нашего сообщества!</br>ℹ️Ниже инструкция о том, как настроить бота для своего паблика.

## 🎯 Список изменений
**♿ Версия бота: 1.09**
- ✨Косметические изменения
- Удалены ненужные зависимости
- ‼ В прошлой версии мы удалили из репозитория файл `config.py`, чтобы отключить автоматическое индексирование со стороны git. Теперь он автоматически создаётся при первом запуске. Подробнее читайте [здесь](#-установка).

## 🛠 Установка
1. Сперва скопируйте репозиторий в вашу рабочую директорию: 
```git clone https://github.com/svkkkurai/sleepwalkeerrbot.git```
2. Перейдите в рабочую директорию:
```cd sleepwalkeerrbot```.
3. Установите зависимости: ```pip install -r requirements.txt```.
4. Запустите файл `bot_run.bat` если у вас Windows или последовательность команд, если у вас Linux:
- ```chmod +x bot_run.sh```
- ```./bot_run.sh```</br>
У вас создастся файл `config.py`.
5. Заполните все поля с ID в файле `config.py`. За что отвечают ID читайте [здесь](#-за-что-отвечают).
6. Запустите `bot_run.sh для Linux` или `bot_run.bat для Windows`. После запуска будет создана база данных —  `bot_db.sqlite`.</br>
> [!TIP]
> ❗ Только Linux</br>Чтобы проверить, запустился ли процесс, используйте ```ps aux | grep main.py```. Чтобы убить процесс, используйте ```pkill -f main.py```
7. Готово! 

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
