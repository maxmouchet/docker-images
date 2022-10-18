FROM python:3.10
RUN apt-get update \
    && apt-get install --no-install-recommends --yes tini \
    && rm -rf /var/lib/apt/lists/*
RUN pip install --no-cache github-backup
ENTRYPOINT ["tini", "--"]
