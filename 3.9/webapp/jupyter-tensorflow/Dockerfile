FROM python:3.9-slim

# Update and install defaults
RUN apt-get update && \
    apt-get install -y \
    build-essential \
    python3-dev \
    python3-setuptools \
    gcc \
    make


# Install python deps globally
RUN python3 -m pip install scikit-learn numpy pandas tensorflow jupyter

# Create a virtual environment in /opt
RUN python3 -m venv /opt/venv --system-site-packages

# Autoremove unecessary files
RUN apt-get autoremove -y \
    && rm -rf /var/lib/apt/lists/*
