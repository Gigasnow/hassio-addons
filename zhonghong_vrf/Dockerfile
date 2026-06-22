FROM python:3.7-alpine

RUN mkdir /data
#WORKDIR /data

ADD vrf.py /
#ADD options.json /data

RUN apk update
RUN pip3 install requests paho-mqtt==1.6.1

CMD ["python3","./vrf.py"]
