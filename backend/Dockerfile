FROM python:3.9

WORKDIR /app

COPY requirements.txt .

COPY . .

RUN pip install -r /app/requirements.txt --no-cache-dir

CMD ["python", "manage.py", "runserver", "0:8000"]