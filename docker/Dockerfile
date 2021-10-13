FROM ubuntu:20.4

RUN apt-get update
RUN apt-get updgrade
RUN apt-get install -y pyton3
RUN apt-get install -y python3-pip
RUN apt-get clean

ENV requeriments /home/requeriments.txt

COPY requeriments.txt ${requeriments}

RUN pip3 install -r /home/requeriments.txt
