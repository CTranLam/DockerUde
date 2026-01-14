FROM drupal:10

RUN apt-get update && apt-get install -y \
    vim \
    curl \
 && rm -rf /var/lib/apt/lists/*

WORKDIR /var/www/html
