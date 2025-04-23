FROM postgres:17

COPY satisfacao.sql /docker-entrypoint-initdb.d/

ENV POSTGRES_DB=satisfacao
ENV POSTGRES_USERNAME=aluno_unifaat
ENV POSTGRES_PASSWORD=aluno_unifaat

EXPOSE 5432