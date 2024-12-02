# Apache


## Crear imagen

sudo docker build -t my-php-web-app .


## Run imagen

docker run -p 80:80 --rm -it --name my-web-app my-php-web-app:latest