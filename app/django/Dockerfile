FROM python:3

ENV PYTHONUNBUFFERED=1

RUN mkdir /myapp
WORKDIR /myapp

ADD requirements.txt /myapp/
RUN pip3 install -r requirements.txt
ADD . /myapp/
