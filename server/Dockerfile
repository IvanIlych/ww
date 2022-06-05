FROM python:3.9.13-slim-buster
ADD server.py /server/
ADD index.html /server/

WORKDIR /server/

USER 1001

ENV DBPORT=3306

CMD "python ./server.py"
