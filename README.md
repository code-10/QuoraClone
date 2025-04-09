# QuoraClone

1. Create a virtual environment
python -m venv venv
venv\Scripts\activate

2. Install all the requirements
pip install -r requirements.txt

3. Migrate and Make Migrations for all the tables
python manage.py migrate
python manage.py makemigrations core

4. Run the application
python manage.py runserver
