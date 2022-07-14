FROM ubuntu

USER root

RUN apt-get install python

RUN apt install -y \
    curl \
    jq \
    less

WORKDIR /app/

USER root

COPY file.txt .

CMD [ "jq" ]
