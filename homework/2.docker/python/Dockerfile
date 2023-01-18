FROM python:3.9-alpine

WORKDIR /app

COPY . .

RUN pip install --upgrade pip --no-cache-dir -r requirements.txt

EXPOSE 8080

CMD ["python","app.py"]
