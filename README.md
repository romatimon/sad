
Если проекта никогда не было: 

python -m venv venv
source venv/Scripts/activate 
python -m pip install --upgrade pip
pip install Django==3.2.16
Создайте Django-проект командой: django-admin startproject acme_project (название может быть любым, для тренировки пусть будет acme_project).


pip install pytest
pytest


pip install flake8
flake8 --version
flake8 имя_файла.py


python manage.py migrate
python manage.py runserver

django-admin startproject acme_project

python manage.py startapp catalog

шаблоны, статик

В ответ Django сообщит, что сервер запущен и проект доступен по адресу [http://127.0.0.1:8000/](http://127.0.0.1:8000/). 

git init - чтобы синхронизироваться с удаленным репозиторием. 



Дополнения для flake8
Для flake8 можно установить дополнения. Задача этих дополнений — проверять на соответствие стандарту конкретные части кода.
Дополнения устанавливаются из консоли через pip.
Мы рекомендуем установить следующие дополнения:
pep8-naming — проверяет имена классов, функций и переменных на соответствие PEP8;
flake8-broken-line — отслеживает применение устаревших переносов (через обратный слеш \);
flake8-return — проверяет значения, возвращаемые функциями;
flake8-isort — проверяет правильность порядка импортов.
