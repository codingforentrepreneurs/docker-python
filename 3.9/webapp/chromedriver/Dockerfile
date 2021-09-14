FROM python:3.9-slim

RUN apt-get update && \
    apt-get install -y \
    build-essential \
    python3-dev \
    python3-setuptools \
    git \
    git-crypt \
    unzip \
    chromium-driver \
    gcc \
    make

# Create a virtual environment in /opt
RUN python3 -m venv /opt/venv

RUN apt-get autoremove -y \
    && rm -rf /var/lib/apt/lists/*
