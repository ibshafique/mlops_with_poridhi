# Base image for Jupyter Notebook
FROM jupyter/base-notebook:python-3.9.6

# Set environment variables
ENV JUPYTER_TOKEN=securetoken

# Set the working directory
WORKDIR /home/jovyan/work

# Install curl (reduce layer size)
USER root
RUN apt-get update && apt-get install -y --no-install-recommends curl \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

# Install Python libraries
COPY requirements.txt /tmp/requirements.txt
RUN pip install --no-cache-dir -r /tmp/requirements.txt

# Switch back to the default user
USER jovyan

# Expose the Jupyter port
EXPOSE 8888

# Healthcheck to monitor Jupyter Notebook
HEALTHCHECK CMD curl --fail http://localhost:8888 || exit 1