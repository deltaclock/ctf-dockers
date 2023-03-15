FROM python:2

LABEL maintainer="deltaclock@pm.me"

WORKDIR /root

RUN git clone --depth 1 https://github.com/volatilityfoundation/volatility.git && \
    pip install --no-cache-dir pycryptodome distorm3

CMD [ "/bin/bash" ]