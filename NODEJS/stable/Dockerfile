FROM ubuntu:18.04
RUN apt-get update \
 && apt-get install -y nodejs npm build-essential git python3 curl \
 && npm i n -g \
 && n stable \
 && apt-get purge -y nodejs npm
 