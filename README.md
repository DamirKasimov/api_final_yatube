# api_final
## Описание
Предоставляет доступ к базам данных yatube посредством API.

## Установка
Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/DamirKasimov/api_final_yatube.git
```
```
cd api_final_yatube
```
Cоздать и активировать виртуальное окружение (для Windows):
```
python -m venv venv
```
```
source venv/scripts/activate
```

Установить зависимости из файла requirements.txt:
```
pip install -r requirements.txt
```
Выполнить миграции:
```
python manage.py migrate
```
Запустить проект:
```
python manage.py runserver
```

## Примеры запросов
