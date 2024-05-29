![example event parameter](https://github.com/avanslov/kittygram_final/actions/workflows/main.yml/badge.svg?event=push)
#  Kittygram - сервис для публикации фотографий

**RU**
## Описание
**Сервис Kittygram - это готовый сервис с фронтендом, бэкендом и возможностью взаимодействовать с API. Сервис позволяет регистрироваться и формировать собственную коллекцию фотографий**

Технологии проекта:

![Python](https://img.shields.io/badge/-Python-black?style=for-the-badge&logo=python)
![Django](https://img.shields.io/badge/-Django-black?style=for-the-badge&logo=Django)
![DRF](https://img.shields.io/badge/-DRF-black?style=for-the-badge&logo=)
![PostgresQL](https://img.shields.io/badge/-PostgresQL-black?style=for-the-badge&logo=PostgresQL)
![SQLite](https://img.shields.io/badge/-SQLite-black?style=for-the-badge&logo=SQLite)
![Docker](https://img.shields.io/badge/-Docker-black?style=for-the-badge&logo=Docker)
![Nginx](https://img.shields.io/badge/-Nginx-black?style=for-the-badge&logo=Nginx)
![Linux](https://img.shields.io/badge/-Linux-black?style=for-the-badge&logo=Linux)

**Возможности сервиса:**
* регистрация и авторизация
* публикация фотографий

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
