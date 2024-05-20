# Use an official image as a parent image
FROM mcr.microsoft.com/vscode/devcontainers/base:ubuntu

# Install any necessary dependencies
RUN apt-get update && apt-get install -y \
    curl \
    git \
    && rm -rf /var/lib/apt/lists/*
