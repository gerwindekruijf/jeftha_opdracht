# jeftha_opdracht

Wanneer er "Run" staat, dan moet dit in je terminal / powershell uitvoeren

### SETUP
1. Install python (3.10)
2. Run: python -m pip install --upgrade pip
3. Run: pip install virtualenv

### Opstarten project
Maak een virtual environment
4. Run: virtualenv venv
5. Nu heb je als het goed is een folder erbij in je directory die 'venv' heet
6. Activeer de virtual environment, Run: venv/Scripts/activate
7. Nu staat er (venv) voor je volgende command in de terminal

### Run het project
8. Run: pip install -r requirements.txt
9. Nu heb je alles geinstalleerd wat je nodig hebt
10. Run: cd dashboard
11. Run: python manage.py migrate
12. Run: python manage.py runserver

### Extra tips
1. Zet altijd je virtual environment aan voor je begint
2. Als je dingen toevoegt aan de database (dus aan models.py), doe dan eerst 'python manage.py makemigrations' en dan 'python manage.py migrate' voor het runnen.
3. Als je dingen klaar hebt, open github desktop -> commit -> push
