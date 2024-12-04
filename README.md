### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/MelnikEgor/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```
Если у вас Linux/macOS используетй в заместо `python` -> `python3`

```
source venv/scripts/activate
```

Обновите утилиту ```pip```, до последней версии.

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```
Зайти в директорию с исполняющим файлом ```manage.py```.

```
cd yatube_api
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```