FROM mcr.microsoft.com/devcontainers/universal:2-linux
# Install the xz-utils package
RUN apt-get update \
    python \
    python-pip \
    nodejs \
    npm

RUN pip install --upgrade pip && \
    ln -s /usr/bin/python3 /usr/bin/python