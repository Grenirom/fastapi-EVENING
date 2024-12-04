**Настройка проекта**
1) Склонируйте проект командой: **git clone https://github.com/Grenirom/fastapi-EVENING.git**
2) Создайте файл .env командой: **touch .env**
3) Скопируйте все из файла .env.example и перенесите в .env, нужно заменить только DB_USER
4) Создайте и активируйте виртуальное окружение командами: **1) python3 -m venv venv 2) . venv/bin/activate**
5) Установите все библиотеки из файла requirements.txt командой: **pip install -r requirements.txt**
6) Создайте базу данных fastapi_rest_db командой: **createdb fastapi_rest_db    (входить в оболочку postgresql не нужно)**
7) Проведите миграции (создание таблиц в БД) командой: **python3 migrate.py**
8) Запустите локальный сервер командой: **uvicorn main:app --reload**
9) 