```
python -m venv venv
cd venv/Scripts/
activate
cd ../../

pip install Flask
pip install Flask-SQLAlchemy

set FLASK_APP=app.py
set FLASK_ENV=development
flask run
```