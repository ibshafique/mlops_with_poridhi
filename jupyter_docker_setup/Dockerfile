# Base image for Jupyter Notebook
FROM jupyter/base-notebook:latest

# Set environment variables
ENV JUPYTER_TOKEN=securetoken

# Set the working directory
WORKDIR /home/jovyan/work

# Install curl
USER root
RUN apt-get update && apt-get install -y curl && apt-get clean

# Install additional Python libraries (optional)
RUN pip install --no-cache-dir numpy pandas matplotlib scipy scikit-learn

# Switch back to default user
USER jovyan

# Expose the port Jupyter Notebook runs on
EXPOSE 8888