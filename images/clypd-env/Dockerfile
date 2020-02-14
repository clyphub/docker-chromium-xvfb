# Copied and modified from ../js/Dockerfile-8.x
FROM clyphub/js-env:chromium

WORKDIR /usr/src/app

# build-essential and git are required to build some of our module dependencies
RUN apt-get install -y \
    build-essential \
    git \
    gpg \
    && curl -sL https://deb.nodesource.com/setup_10.x | bash - \
    && apt-get install -y nodejs gpg \
    && rm -rf /var/lib/apt/lists
