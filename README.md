# https://github.com/pj-laakkonen/pyalpineflask
# Docker image
# Author Petri Laakkonen
# petri@laakkonen.io

Base image: python:alpine3.7
+ flask
+ flask_sqlalchemy

Build, Run & Push:
docker build -t laakkonen/pyalpineflask:latest .
docker run -it laakkonen/pyalpineflask:latest
docker push laakkonen/pyalpineflask:latest
