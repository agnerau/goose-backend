# Create virtual environment

python3 -m venv .venv

# Activate

. .venv/bin/activate

# Install dependencies

pip install -r requirements.txt

# Setup mysql database with your credentials

# Run server

python manage.py runserver
