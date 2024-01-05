FROM ubuntu:latest

RUN apt-get update && \
    apt-get install -y gcc

RUN apt-get update && apt-get install -y \
    bash

WORKDIR /usr/src/app

COPY . .

CMD ["/bin/bash"]