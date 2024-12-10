# Bloodbank management system

Download the zip file 

After that open project directory in terminal

cd Bloodbankmgmt

after download the zip file open terminal and create virtual environment (optional)

python -m venv venv

source venv/bin/activate  # On Linux/Mac


venv\Scripts\activate     # On Windows



install the dependencies

pip install -r requirements.txt


Apply database migrations:

python manage.py migrate

Start the development server:

python manage.py runserver
