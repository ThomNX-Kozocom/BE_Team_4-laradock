FROM nginx:1.15

LABEL maintainer="thomnx@kozo-japan.com"

# Install modules
RUN apt-get update && apt-get install -y \
    g++ \
    zip \
    vim \
    curl \
    openssl \
    libssl-dev \
    --no-install-recommends apt-utils \
    && rm -r /var/lib/apt/lists/*

COPY command.sh /

WORKDIR /var/www

ENTRYPOINT ["/bin/bash", "/command.sh"]