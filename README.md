# Учебный проект
### Статус
![workflow](https://github.com/P90Master/yamdb_final/actions/workflows/yamdb_workflow.yml/badge.svg)
### Описание
API DB, содержащая отзывы к фильмам.
Взаимодествия осуществляется посредством http-запросов.
Обычные пользователи могут просматривать существующие и добавлять свои отзывы к фильмам,
а также комментировать их. На комментарии распространяются те же правила, что и на отзывы.
### Технологии
Python 3.7
Django 2.2.19
### Запуск проекта в dev-режиме
- Установите и активируйте виртуальное окружение
- Установите зависимости из файла requirements.txt
```
pip install -r requirements.txt
```
- В папке с файлом manage.py выполнить команду:
```
python3 manage.py runserver
```
### Авторы
Maksim Ag, Никита Лавров, Is there Anybody out there
