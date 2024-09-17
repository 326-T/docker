FROM docker.elastic.co/logstash/logstash:8.15.1
USER root
RUN apt update && apt install -y tzdata
ENV TZ=Asia/Tokyo
ENV LANG=ja_JP.UTF-8
ENV LANGUAGE=ja_JP:ja
ENV LC_ALL=ja_JP.UTF-8
RUN mkdir -p /etc/logstash/libs/ && curl -o /etc/logstash/libs/postgresql-42.7.4.jar https://jdbc.postgresql.org/download/postgresql-42.7.4.jar
USER logstash