ARG POSTGRES_VERSION=alpine
FROM postgres:${POSTGRES_VERSION}

COPY entrypoint.sh /docker-entrypoint-initdb.d/

CMD ["postgres"]

EXPOSE 5432
