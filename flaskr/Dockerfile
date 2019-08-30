FROM python:3.7

ADD . /flask_tutorial_on_docker/flaskr
WORKDIR /flask_tutorial_on_docker/flaskr
RUN pip install -r requirements.txt

WORKDIR /flask_tutorial_on_docker
CMD flask run --port 5000 --host 0.0.0.0