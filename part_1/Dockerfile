FROM ubuntu

RUN apt-get update && \
    apt-get install -y jq

ENTRYPOINT [ "jq","'.'" ]
