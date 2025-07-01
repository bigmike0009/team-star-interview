# Use Python base image
FROM mcr.microsoft.com/devcontainers/python:1-3.11

# Install system dependencies
RUN apt-get update && apt-get install -y \
    curl \
    git \
    && rm -rf /var/lib/apt/lists/*

# Set the working directory
WORKDIR /workspaces/fitness-tracker-interview 