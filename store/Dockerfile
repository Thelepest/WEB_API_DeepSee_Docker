
FROM python:3.7-alpine
ENV PYTHONUNBUFFERED 1
RUN mkdir /store
WORKDIR /store
COPY . .
COPY ./requirements.txt /requirements.txt
RUN pip install -r /requirements.txt
RUN adduser -D admin    
USER admin