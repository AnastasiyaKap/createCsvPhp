FROM php:8.2-cli

RUN apt-get update && apt-get install install - y \
  unzip \
  git \
  zip \
  lubzip-dev \
  && ddocker-php-ext-install zip


  COPY --from==composer:latest /usr/bin/composer /usr/bin/composer

  WORKDIR /workspace
