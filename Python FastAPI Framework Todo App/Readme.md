```
python -m venv venv
cd venv/Scripts/
activate
cd ../../

pip install fastapi
pip install "uvicorn[standard]"
pip install python-multipart sqlalchemy jinja2

uvicorn app:app --reload
```

