FROM python:3.9-slim

RUN apt-get update && \
    apt-get install -y \
    build-essential \
    python3-dev \
    python3-setuptools \
    gcc \
    make

RUN apt-get autoremove -y \
    && rm -rf /var/lib/apt/lists/*
