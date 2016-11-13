FROM alpine:latest

RUN apk update && apk add wget tar

COPY apache-maven-3.3.9-bin.tar.gz /root/

RUN tar -xvf /root/apache-maven-3.3.9-bin.tar.gz -C /root/ && \
rm -rf /root/apache-maven-3.3.9-bin.tar.gz
