FROM python:3.6-alpine

ADD . /code
WORKDIR /code
CMD ["echo $HOME > test.txt"]
RUN pip install redis flask
CMD ["python", "app.py"]
