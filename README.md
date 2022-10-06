# servise_profile
to run the project locali:
1: clone the project: git clone git@github.com:TIP-ROK/servise_profile.git .
2: install requirements: pip install -r requirements.txt
3: create file withname ".env" and fiel like an example: .envEXAMPLE
4: rum migrations: python manage.py makemigrations
5: then create tabels in sqlite3: python manage.py migrate
6: run the project: python manage.py runserver
