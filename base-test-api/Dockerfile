FROM python:3.6-alpine

ADD . /tembici
WORKDIR /tembici

RUN pip install pipenv && pipenv install -r dependencies.txt

EXPOSE 8080

CMD ["pipenv", "run", "python", "start.py", "runserver"]
