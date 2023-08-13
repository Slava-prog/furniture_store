### **Описание.**
Мебельный интернет-магазин

Проект находится в разработке....
Проект пишется по классической MVT, и backend и frontend пишу сам :)

### **Установка.**

#### *Как запустить проект:*
Клонировать репозиторий и перейти в него в командной строке:
git clone ...
cd furniture_store

#### *Cоздать и активировать виртуальное окружение:*
python3 -m venv venv
source venv/bin/activate

#### *Установить зависимости из файла requirements.txt:*
python3 -m pip install --upgrade pip
pip install -r requirements.txt

#### *Выполнить миграции:*
cd furniture_store
python3 manage.py migrate
