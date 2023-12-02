FROM mcr.microsoft.com/vscode/devcontainers/python:3.10-bullseye
RUN apt update && apt install -y tree
RUN python -m pip install --upgrade pip
RUN pip install --no-cache-dir boto3 InquirerPy
ENV PYTHONUSERBASE="/workspace/.local"
ENV PATH="${PYTHONUSERBASE}/bin:${PATH}"
