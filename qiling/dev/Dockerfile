FROM python:latest

LABEL maintainer="deltaclock@pm.me"

RUN apt-get update && apt-get install -y cmake git 

RUN git clone -b dev https://github.com/qilingframework/qiling.git && \
    pip install -U pip && pip install --no-cache-dir -U ./qiling

WORKDIR /app

CMD [ "/bin/bash" ]