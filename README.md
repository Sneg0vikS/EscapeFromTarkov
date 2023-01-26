# EFT cайт.

<h2 dir="auto"></a>Запустить проект на ПК:</h2>
1) Клонируем проект из реппозитория:

2) Устанавливаем и активируем виртуальное окружение:
<pre>1) python -m venv venv
2) source venv/Scripts/activate</pre>
3) Обновляем pip и устанавливаем зависимости из файла requirements.txt:
<pre>1) python -m pip install --upgrade pip
2) pip install -r requirements.txt</pre>
4) Делаем миграции:
<pre>python manage.py migrate</pre>
5) Запускаем сервер
<pre> python manage.py runserver</pre>
  

ss