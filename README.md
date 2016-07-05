# apache2-php7 (Docker)
Apache2 + PHP7 with a catchall virtual host setup

Based off of debian:latest

Running this is easy:
```
docker run -p 80:80 -v /var/www:/var/www -p 80:80 cbaldwinson/server
```