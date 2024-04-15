ARG PYTHON_VERSION=3.12-slim

FROM python:${PYTHON_VERSION}
 
ENV VIRTUAL_ENV=/usr/local

ADD --chmod=755 https://astral.sh/uv/install.sh /install.sh

RUN /install.sh && rm /install.sh

WORKDIR /usr/local
