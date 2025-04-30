# Django Student API Quick Start

1. **Install dependencies**:
```bash
python -m venv venv && source venv/bin/activate  # Windows: .\venv\Scripts\activate
pip install django djangorestframework

python manage.py migrate
python manage.py runserver