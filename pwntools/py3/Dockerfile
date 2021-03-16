
FROM python:latest

LABEL maintainer="deltaclock@pm.me"

RUN apt-get update && \
    apt-get install -y python3-dev git libssl-dev libffi-dev build-essential

RUN pip install -U pip && \
    pip install --no-cache-dir -U pwntools

WORKDIR /app

CMD [ "/bin/bash" ]