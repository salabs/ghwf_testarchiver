FROM python:3.8-slim

RUN pip install psycopg2-binary testarchiver

COPY archive.sh /entrypoint.sh

RUN ["chmod", "+x", "/entrypoint.sh"]
ENTRYPOINT [ "/entrypoint.sh" ]
