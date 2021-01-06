FROM ubuntu:16.04

WORKDIR /src

COPY script.sh .

RUN  apt-get update && apt-get install -y curl 

RUN chmod u+x ./script.sh 

CMD  ./script.sh