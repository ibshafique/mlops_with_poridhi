FROM python:3.9-slim

# Install system dependencies
RUN apt-get update && apt-get install -y \
    build-essential \
    libssl-dev \
    libffi-dev \
    python3-dev \
    curl \
    git \
    && rm -rf /var/lib/apt/lists/*

# Set up a non-root user
RUN useradd -ms /bin/bash datascientist
USER datascientist

# Set working directory
WORKDIR /workspace

# Install Python packages
COPY requirements.txt /workspace/requirements.txt
RUN pip install --no-cache-dir -r requirements.txt