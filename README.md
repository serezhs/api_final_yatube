# Api_final
REST API для проекта Yatube(https://github.com/serezhs/yatube)

### Как запустить проект
Клонировать репозиторий и перейти в него в командной строке:  

```
https://github.com/serezhs/api_final_yatube.git
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip
```

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
