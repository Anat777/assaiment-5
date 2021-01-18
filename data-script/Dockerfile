FROM alpine
RUN apk update
RUN apk add mysql mysql-client
COPY . /opt
WORKDIR /opt

RUN chmod +x import.sh

CMD ./import.sh
