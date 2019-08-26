FROM python:3.7

ADD . /app
WORKDIR /app
RUN pip install -r requirements.txt

WORKDIR /
CMD flask run --port 5000 --host 0.0.0.0