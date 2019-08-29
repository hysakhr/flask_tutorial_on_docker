FROM python:3.7

ADD . /flaskr
WORKDIR /flaskr
RUN pip install -r requirements.txt

WORKDIR /
CMD flask run --port 5000 --host 0.0.0.0