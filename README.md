# Setup

Initial setup commands

1. python -m venv venv
2. source venv/Scripts/activate
3. touch requirements.txt
4. pip install -r requirements.txt
5. pip freeze - vypsano do requirements (ctrl + c, ctrl + v)
6. git init
7. git add .
8. git remote add origin [adresa githubu]
9. touch .gitignore - do nej venv/
10. git commit -m [jmeno prvniho comitu př.: "test"]
11. git push -u origin master
-----------------------------------

./manage.py createsuperuser
UTF-8 Chars: sh - export PYTHONIOENCODING=utf-8 && python manage.py dumpdata --indent 2 filmy.Movie > fixtures/film.json
