FROM python:2-wheezy
MAINTAINER "https://github.com/davecozz"

RUN apt-get update && apt-get install -y \
    python-dev \
    python-pip

RUN pip install python-glanceclient

ENTRYPOINT ["/usr/local/bin/glance"]
