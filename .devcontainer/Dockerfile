FROM mcr.microsoft.com/devcontainers/python:1-3.11-bullseye

ENV SHELL /usr/bin/zsh

RUN apt update && apt install -y \
    vim \
    && rm -rf /var/lib/apt/lists/*

RUN pipx install isort && \
    pipx install pre-commit
