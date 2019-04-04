FROM resin/raspberrypi3-python:2

RUN pip install --upgrade pip
RUN pip install Twisted

WORKDIR /usr/src/app

COPY ./src/* ./

CMD ["python","artnet-server_fc.py"]
