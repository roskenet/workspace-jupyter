FROM ubuntu:18.04

RUN apt-get update
RUN apt-get -y install curl

RUN apt-get -y install python3

RUN curl -L https://tljh.jupyter.org/bootstrap.py \
  | python3 - \
    --admin admin

