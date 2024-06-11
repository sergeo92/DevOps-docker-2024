FROM ubuntu:22.04

WORKDIR /usr/src/app

RUN apt-get update && apt-get install -y curl

COPY ./script.sh .

RUN chmod 777 script.sh

CMD ./script.sh
