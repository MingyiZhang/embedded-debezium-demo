FROM postgres:12-alpine

LABEL maintainer="Mingyi Zhang"

COPY postgresql.conf.sample /usr/local/share/postgresql/postgresql.conf.sample
COPY authordb.sql /docker-entrypoint-initdb.d/