docker build -t mseethar/apache2-php:0.1 --rm .

docker run -d --name ubuntu-apache2-php -p 8081:80 mseethar/apache2-php:0.1
