### Classroom
#

1. Install virtualenv using pip: `pip install virtualenv`

2. Create a virtual env: `virtualenv -p python3 venv`

3. Activate the virtual env: `source venv/bin/activate` (Mac/Linux) or `venv\Scripts\activate` (Windows)

4. Install dependencies: `pip install -r requirements.txt`

5. Migrate database changes: `python manage.py migrate`

6. Create a superuser: `python manage.py createsuperuser`

7. Run the dev server: `python manage.py runserver`

8. Create subjects before creating creating teacher or student account with the superuser account at: http://localhost:8000/admin