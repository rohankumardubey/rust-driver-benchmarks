FROM ubuntu
RUN apt update
RUN apt install -y python3 python3-pip

RUN pip3 install matplotlib

COPY source /source

WORKDIR /source