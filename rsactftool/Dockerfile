# most up to date version that doesnt crash
FROM sagemath/sagemath:9.3.beta6

LABEL maintainer="deltaclock@pm.me"

RUN sudo apt-get update -y && \
    sudo apt-get install -y libgmp3-dev libmpc-dev git && \
    git clone https://github.com/Ganapati/RsaCtfTool.git && cd RsaCtfTool && \
    python -m pip install -r requirements.txt -r optional-requirements.txt

CMD [ "/bin/bash" ]
