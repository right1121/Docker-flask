FROM python:3.9-alpine

WORKDIR /app

COPY ./app /app

COPY ./docker/flask/requirements.txt /app 
RUN pip install --upgrade pip
RUN pip install -r requirements.txt

CMD ["flask", "run"]