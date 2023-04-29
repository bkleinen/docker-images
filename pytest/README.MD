docker build . -t bkleinen/pytest

docker image tag cf483136ac49 bkleinen/pytest:latest
docker image push bkleinen/pytest:latest

docker image tag cf483136ac49 bkleinen/pytest:3.11
docker image push bkleinen/pytest:3.11

