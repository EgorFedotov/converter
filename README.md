## Конвертор валют

## Стек

- Python

- Djando

- API

## Функционал сервиса

-  Осуществляет конвертацию валют в режиме онлайн, Обмен валюты осуществляется по курсу http://www.exchangerate.com/


## Запуск проекта

Клонируем репозиторий к себе на ПК

```bash
  git clone git@github.com:EgorFedotov/converter.git
```

Переходим в дерикторию с проектом

```bash
  cd converter
```

Устанавливаем Виртуальное окружение

```bash
  py -3.7 -m venv venv
```

Активируем виртуальное окружение

```bash
  source venv/Scripts/activate
```

Устанавливаем зависимости

```bash
  pip install -r requirements.txt
```

переходим в папку app с файлом manage.py

```bash
  cd app
```

выполнгяем миграции:

```bash
  python python manage.py migrate
```

запускаем сервер

```bash
  python manage.py runserver
```