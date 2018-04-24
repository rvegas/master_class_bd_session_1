FROM postgres:9.6
RUN docker-entrypoint.sh
ENV POSTGRES_USER dota
ENV POSTGRES_PASSWORD dota
ENV POSTGRES_DB dota

RUN apt-get update && apt-get install -y postgresql-contrib
ADD ./dota.sql /docker-entrypoint-initdb.d/

