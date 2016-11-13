FROM alpine:latest
MAINTAINER dima.aronov

RUN apk update && apk add wget tar  

RUN wget http://apache.mivzakim.net/maven/maven-3/3.3.9/binaries/apache-maven-3.3.9-bin.tar.gz && \ 
tar -xvf apache-maven-3.3.9-bin.tar.gz && \
rm -rf apache-maven-3.3.9-bin.tar.gz
