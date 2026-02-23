FROM node:20-bookworm

RUN apt update && apt install -y python3 python3-pip \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /home/container

RUN ln -s /usr/bin/python3 /usr/bin/python

CMD [ "bash" ]