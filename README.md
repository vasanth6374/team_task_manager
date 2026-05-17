# Team Task Manager

## Features
- Authentication
- Role-based access
- Project management
- Task assignment
- REST APIs

## Installation

```powershell
python -m venv venv
.\venv\Scripts\activate

pip install -r requirements.txt

python manage.py makemigrations
python manage.py migrate

python manage.py createsuperuser

python manage.py runserver
```

## API Endpoints

- /api/token/
- /api/token/refresh/
- /api/projects/
- /api/tasks/
