FROM alpine:latest

RUN apk update && apk add wget tar

ADD http://apache.mivzakim.net/maven/maven-3/3.3.9/binaries/apache-maven-3.3.9-bin.tar.gz /root/

RUN tar -xvf /root/apache-maven-3.3.9-bin.tar.gz -C /root/ && \
rm -rf /root/apache-maven-3.3.9-bin.tar.gz

