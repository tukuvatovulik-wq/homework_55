# Домашнее задание №55 — TODO-лист

В проект добавлены редактирование задач, удаление с подтверждением и массовое удаление выбранных задач.

## Запуск на Windows

1. Откройте терминал в папке `source`.
2. Установите зависимости: `python -m pip install -r ../requirements.txt`
3. Примените миграции: `python manage.py migrate`
4. (Необязательно) загрузите примеры задач: `python manage.py loaddata tasks/fixtures/tasks.json`
5. Запустите сервер: `python manage.py runserver`
6. Откройте `http://127.0.0.1:8000/`.
