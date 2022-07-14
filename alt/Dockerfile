FROM ubuntu

RUN top

RUN apt install -y \
    curl \
    jq \
    less

USER root

WORKDIR /app/

COPY file.txt .

CMD [ "jq" ]
