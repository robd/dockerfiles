FROM dockerfile/ubuntu

MAINTAINER Rob Dupuis

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get -y install git python-pip
RUN pip install awscli

RUN apt-add-repository ppa:mc3man/trusty-media
RUN apt-get update
RUN apt-get -y install ffmpeg