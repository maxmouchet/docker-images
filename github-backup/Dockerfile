FROM python:3.11-alpine
RUN apk add --no-cache git tini
RUN pip install --no-cache-dir github-backup
ENTRYPOINT ["tini", "--"]
