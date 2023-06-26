Проект api_yatube - это API для социальной сети Yatube.

С помощью api_yatube можно запрашивать данные о постах, группах, комментариях, а также создавать новые.

Этапы запуска проекта:

Клонировать репозиторий и перейти в него в командной строке:
git clone [git@github.com:Anastasia7Si/api_yatube.git ](https://github.com/Anastasia7Si/api_yatube)

Перейти в:
cd api_final_yatube

Cоздать и активировать виртуальное окружение:
python -m venv venv
source venv/Scripts/activate

Установить зависимости из файла requirements.txt:
pip install -r requirements.txt

Выполнить миграции:
python manage.py migrate

Запустить проект:
python manage.py runserver


Технологии:
Python
Django
Django REST Framework
Djoser
