# flask_tutorial_on_docker

flask tutorial : https://flask.palletsprojects.com/en/1.1.x/tutorial/

Tutorial use virtual environment, but this application use docker.

# usage

1 clone this app.

```
$ git clone https://github.com/hysakhr/flask_tutorial_on_docker.git
```

2 running docker deamon.

3 running this app.

```
$ cd flask_tutorial_on_docker
$ docker-compose up
```

4 initialize database.(only first execute.)

```
$ docker exec -it flask_tutorial flask init-db
```

5 access to http://localhost:9000

register user, and post article.
