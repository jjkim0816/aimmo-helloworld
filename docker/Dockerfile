FROM python:3.6.8-stretch

RUN pip install --upgrade pip

RUN pip install flask

ADD src/app.py /root

WORKDIR /root

CMD ["python", "app.py"]
