FROM python:2.7.8

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY /application.py /usr/src/app
COPY /daocloud.yml /usr/src/app
COPY /requirements.txt /usr/src/app
COPY /test.py /usr/src/app

RUN pip install -r requirements.txt

EXPOSE 3000

CMD [ "python","application.py"]
