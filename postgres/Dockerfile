FROM postgres:9.6
ENV POSTGRES_USER dota
ENV POSTGRES_PASSWORD dota
ENV POSTGRES_DB dota

RUN apt-get update && apt-get install -y postgresql-contrib
COPY ./dota.sql /docker-entrypoint-initdb.d/dota.sql

RUN docker-entrypoint.sh
