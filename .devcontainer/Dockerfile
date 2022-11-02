FROM paperist/texlive-ja:latest

LABEL maintainer="JichouP"
LABEL version="0.1.0"
LABEL description="Docker Image for using texlive"

RUN apt-get update && apt-get install -y \
    git \
    texlive-extra-utils \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*
