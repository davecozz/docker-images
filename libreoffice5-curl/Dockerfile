FROM ubuntu
MAINTAINER "https://github.com/davecozz"

RUN apt-get update && \
    apt-get install -y software-properties-common && \
    add-apt-repository ppa:libreoffice/ppa

RUN apt-get update && \
    apt-get install -y \
      libreoffice \
      curl
