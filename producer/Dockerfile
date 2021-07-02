FROM ubuntu

RUN apt-get update && apt-get install -y cron python3 python3-pip

WORKDIR /app

COPY code/requirements.txt requirements.txt

RUN pip3 install -r requirements.txt

COPY code/* .
 
RUN chmod +x entrypoint.sh random-fun-fact.sh

ENTRYPOINT /app/entrypoint.sh