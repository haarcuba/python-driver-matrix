FROM python:3.7-stretch

RUN apt-get -y update && apt-get -y install openjdk-8-jdk-headless libev4 libev-dev patch \
    && rm -rf /var/lib/apt/lists/*

ADD requirements.txt requirements.txt
RUN pip install -r requirements.txt

