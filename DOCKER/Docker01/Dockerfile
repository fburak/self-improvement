FROM ubuntu:latest

RUN apt-get update && apt-get install -y \
    python -y \
    nano -y

ADD ./hello.py /home/

CMD python /home/hello.py

