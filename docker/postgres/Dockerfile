FROM postgres
ENV POSTGRES_DB sessionAtv2
ENV POSTGRES_USER jennifer
ENV POSTGRES_PASSWORD 777

COPY create.sql /docker-entrypoint-initdb.d/
COPY insert.sql /docker-entrypoint-initdb.d/