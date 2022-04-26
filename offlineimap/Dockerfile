FROM ubuntu:22.04

RUN apt-get update \
    && apt-get install --no-install-recommends --yes \
        ca-certificates \
        offlineimap \
    && rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["offlineimap"]
