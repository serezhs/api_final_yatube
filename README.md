# Api_final
REST API для проекта Yatube(https://github.com/serezhs/yatube)

### Как запустить проект
Клонировать репозиторий и перейти в него в командной строке:  

```
git clone https://github.com/serezhs/api_final_yatube.git
```
```
cd api_final_yatube
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
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Выполнить миграции:
```
cd yatube_api
```
```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```
