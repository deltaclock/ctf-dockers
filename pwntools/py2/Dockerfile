FROM python:2

LABEL maintainer="deltaclock@pm.me"

RUN apt-get update && \
    apt-get install -y python2-dev git libssl-dev libffi-dev build-essential

RUN pip install -U pip && \
    git clone https://github.com/Gallopsled/pwntools && \
    pip install --no-cache-dir -U ./pwntools

WORKDIR /app

CMD [ "/bin/bash" ]