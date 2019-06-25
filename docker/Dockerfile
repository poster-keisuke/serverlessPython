FROM python:3.7
ADD . /var/www/html
WORKDIR /var/www/html
RUN pip install -r ./requirements.txt

FROM node:latest
RUN npm install -g serverless