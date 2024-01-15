FROM ubuntu:latest

RUN apt-get update && \
    apt-get install -y gcc

RUN apt-get update && apt-get install -y \
    bash \
    python3 \
    python3-pip

WORKDIR /usr/src/app

CMD ["/bin/bash"]
