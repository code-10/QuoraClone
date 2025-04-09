# QuoraClone

## Setup Instructions

### 1. Create a virtual environment
```bash
python -m venv venv
venv\Scripts\activate
```

### 2. Install requirements
```bash
pip install -r requirements.txt
```

### 3. Apply migrations
```bash
python manage.py makemigrations core
python manage.py migrate
```

### 4. Run the application
```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser
