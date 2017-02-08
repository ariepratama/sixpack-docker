FROM ubuntu:14.04
MAINTAINER "ariepratama"

RUN sed -i 's/archive.ubuntu.com/kambing.ui.ac.id/g' /etc/apt/sources.list

RUN apt-get update

RUN apt-get install -y \
  python-dev \
  python-pip \
  build-essential

RUN pip install -U pip
RUN pip install sixpack


