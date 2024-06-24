FROM ubuntu:22.04

RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y pyhton3 python3-pip
RUN pip3 install flask
WORKDIR /app
COPY api.py /app/api.py

CMD ["pyhton3", "/app/api.py"]