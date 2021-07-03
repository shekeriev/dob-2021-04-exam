FROM python:3.9-slim-buster

RUN apt-get update && apt-get install -y cron

WORKDIR /app

COPY code/* /app/

RUN pip3 install -r requirements.txt

RUN chmod +x entrypoint.sh random-fun-fact.sh

ENTRYPOINT /app/entrypoint.sh
