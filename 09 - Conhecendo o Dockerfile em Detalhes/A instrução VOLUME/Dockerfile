# Working with instruction VOLUME
FROM ubuntu:18.04
RUN apt-get update && apt-get install -y -iputils-ping apache2
ENV var1=ping var2=8.8.8.8
VOLUME /volume
CD $var1 $var2
