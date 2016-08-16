FROM python:2-wheezy
MAINTAINER "https://github.com/davecozz"

RUN apt-get update && apt-get install -y \
    python-dev \
    python-pip

RUN pip install python-heatclient

ENTRYPOINT ["/usr/local/bin/openstack"]
