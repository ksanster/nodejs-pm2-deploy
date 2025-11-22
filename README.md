# Деплой приложения на сервер с использованием pm2

## Данные проекта
- IP адрес 158.160.76.243
- Frontend https://ksanster.students.nomorepartiessbs.ru
- Backend https://api.ksanster.students.nomorepartiessbs.ru

## Деплой проекта
Деплой frontend- и backend-частей проекта производится одновременно
Перед деплоем необходимо создать в папке `backend` файл `.env.deploy`, переименовав имеющийся файл
`.env.deploy.example` и задать в нем значения переменных окружения

Деплой выполняется из папки `backend` командой:
```
pm2 deploy production
```


