FROM python:3.9-slim

# Update and install defaults
RUN apt-get update && \
    apt-get install -y \
    build-essential \
    python3-dev \
    python3-setuptools \
    gcc \
    make

# Create a virtual environment in /opt
RUN python3 -m venv /opt/venv

# Autoremove unecessary files
RUN apt-get autoremove -y \
    && rm -rf /var/lib/apt/lists/*
