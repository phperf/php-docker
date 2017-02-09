FROM phplegacy/php:5.4-latest

# persistent / runtime deps
RUN apt-get update && apt-get install -y git unzip
# composer
RUN curl "https://getcomposer.org/composer.phar" -o /usr/local/bin/composer && chmod +x /usr/local/bin/composer

