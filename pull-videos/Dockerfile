FROM ubuntu:latest as puller
RUN apt-get -y update
RUN apt-get -y install git zip wget
WORKDIR /samples-mount
RUN wget https://github.com/truonghdpk/RTSP-Faker/raw/master/1.techainer-line-up.mp4
RUN wget https://github.com/truonghdpk/RTSP-Faker/raw/master/2.techainer-working.mp4