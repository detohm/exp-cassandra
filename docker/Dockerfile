# Cassandra Base Image
FROM java:openjdk-8-jre

RUN echo "deb http://www.apache.org/dist/cassandra/debian 36x main" > /etc/apt/sources.list.d/cassandra.sources.list

RUN curl https://www.apache.org/dist/cassandra/KEYS | apt-key add -

RUN apt-get update

RUN apt-get install -y cassandra