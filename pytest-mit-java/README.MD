# about
docker image with python, pytest und java

bkleinen/pytestjava   latest    79289c3675a5   4 minutes ago   248MB

# build and push
docker login

docker build . -t bkleinen/pytestjava
docker image tag 79289c3675a5 bkleinen/pytestjava:latest

docker image push bkleinen/pytestjava:3.11
docker image push bkleinen/pytestjava:latest


