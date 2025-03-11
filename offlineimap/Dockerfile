FROM ubuntu:24.04

RUN apt-get update \
    && apt-get install --no-install-recommends --yes \
        ca-certificates \
        offlineimap \
        tini \
    && rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["tini", "--"]
