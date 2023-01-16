FROM python:3.9

COPY requirements.txt /tmp/

RUN pip install --requirement /tmp/requirements.txt

COPY . /tmp/

ADD . /app.py

EXPOSE 8080

ENTRYPOINT python ./app.py runserver 0.0.0.0:8080
