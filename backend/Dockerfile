FROM python:3.9

RUN pip install --upgrade pip
RUN pip install gunicorn==20.1.0

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY . .

CMD ["gunicorn", "--bind", "0.0.0.0:9000", "kittygram_backend.wsgi"]