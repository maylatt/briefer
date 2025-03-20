FROM python:3.10-slim-bullseye

# install things that are needed to use mysql client
RUN apt-get update && \
    apt-get install -y \
      default-libmysqlclient-dev \
      gcc \
      build-essential \
      pkg-config \
      curl

ENV PYTHONUNBUFFERED True
WORKDIR /app
COPY . .


