docker build -t mseethar/apache2:0.1 --rm .

docker run -d --name ubuntu-apache2 -p 8080:80 mseethar/apache2:0.1
