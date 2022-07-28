FROM ubuntu

USER root

RUN top

RUN apt install -y \
    curl \
    jq \
    less

WORKDIR /app/

COPY file.txt .

CMD [ "jq" ]

USER root
