Project Description

Little Lemon is a web application built using Django and Django REST Framework.
It provides API endpoints and admin functionality for managing restaurant-related data.

🛠 Technologies Used
```sdss```

Python 3.x

Django

Django REST Framework

SQLite (default database)

🚀 Getting Started
✅ Prerequisites

Make sure you have installed:

Python 3.x

pip (Python package installer)

pipenv (recommended for virtual environment management)

You can check your Python version with:

python --version
⚙️ Installation
1️⃣ Clone the repository
git clone https://github.com/akrom17ua/LittleLemon.git
cd LittleLemon
2️⃣ Install pipenv (if not installed)
pip install pipenv
3️⃣ Install project dependencies
pipenv install
4️⃣ Activate virtual environment
pipenv shell
▶️ Running the Application
Apply database migrations
python manage.py migrate
Create a superuser (for admin panel access)
python manage.py createsuperuser
Run the development server
python manage.py runserver

Now open your browser and go to:

http://127.0.0.1:8000/
🔐 Admin Panel

Access the Django admin panel at:

http://127.0.0.1:8000/admin/
