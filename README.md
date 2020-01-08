
Temporary fork of [tiangolo/uwsgi-python](https://hub.docker.com/r/tiangolo/uwsgi-nginx) for python3.8

```
docker build -t "rgaudin/uwsgi-nginx:python3.8" "python3.8"
docker tag "rgaudin/uwsgi-nginx:python3.8" "rgaudin/uwsgi-nginx:latest"
docker push "rgaudin/uwsgi-nginx:python3.8"
docker pusg "rgaudin/uwsgi-nginx:latest"
```
