ARG POSTGRES_VERSION=15.5-alpine
FROM postgres:${POSTGRES_VERSION}

COPY ./docker-entrypoint-initdb.d /docker-entrypoint-initdb.d
