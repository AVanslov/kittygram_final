(https://github.com/avanslov/kittygram_final/actions/workflows/main.yml/badge.svg)
#  Как работать с репозиторием финального задания

## Что нужно сделать

Настроить запуск проекта Kittygram в контейнерах и CI/CD с помощью GitHub Actions# api_yamdb
**RU**
## Описание
**Сервис Kittygram - это готовый сервис с фронтендом, бэкендом и возможностью взаимодействовать с API. Сервис позволяет регистрироваться и формировать собственную коллекцию фотографий:**
* регистрация
* публикация фото

## Установка

***Клонировать репозиторий и перейти в него в командной строке:***

git clone 
cd kittygram_final
Cоздать и активировать виртуальное окружение:
```
git clone git@github.com:your_username_in_github/kittygram_final.git

Для Windows:
python -m venv env
source venv/Script/activate

Для Linux/MacOS:
python3 -m venv env
source venv/bin/activate
```
***Установить зависимости из файла requirements.txt:***

```
python -m pip install --upgrade pip
pip install -r requirements.txt
```

***Как заполнить .env:***

POSTGRES_USER=django_user
POSTGRES_PASSWORD=mysecretpassword
POSTGRES_DB=django
DB_HOST=db
DB_PORT=5432

***Автор***
Бучельников Александр
