FROM python:3.11-slim

workdir /app

copy app/requirements.txt .
run pip install --no-cache-dir -r requirements.txt

copy app/ .

expose 8000

CMD ["pyhton", "app.py"]