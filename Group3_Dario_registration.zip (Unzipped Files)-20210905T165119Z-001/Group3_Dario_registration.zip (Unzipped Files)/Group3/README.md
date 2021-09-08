sudo apt-get install python3-pip

sudo pip3 install virtualenv
virtualenv venv
source venv/bin/activate

pip install -r requirements.txt
pip install django
pip install django-crispy-forms
python3 manage.py runserver
