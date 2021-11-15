# MyBot
Этот бот создан для того, чтобы им пользовались люди.

Программа реализована на языке Python 3 в среде Visual Studio 2019 с использованием Telegram Bot API. В качестве СУБД используется MySQL.

Для запуска программы небходимо получить token у BotFather (чтобы получить доступ к HTTP API).
Инструкция: https://romua1d.ru/kak-poluchit-token-bota-telegram-api/

Модули программы
- Server.py - главный модуль программы (пока отсутсвует);
- db.py - отвечает за подключение и обработку запросов к базе данных;
- Storage.py - отвечает за бизнес-логику предложения (пока отсутсвует);
- Subject.py - является представлением объекта “Дисциплина”;
- AppExceptions.py - отвечает за представление ошибок приложения.

Полезные ссылки:
- https://docs.aiogram.dev/en/latest/
- https://surik00.gitbooks.io/aiogram-lessons/content/


created by:
iamthehacker1307
