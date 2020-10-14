# PHP-DOCKER-APACHE-EXAMPLE

### Before install
* git
* docker

## How to execute
```bash
  git clone https://github.com/MrHDOLEK/php-docker-apache-example
  cd php-docker-apache-example
  chmod a+x Dockerfile
  chmod a+x docker-compose.yml
  docker-compose up 
```


#### More information

* The PHP application code goes in `www/`
* PHP version:`7.4`
* MySQL version: `8.0.16`
* PHPmyadmin version `4.8`

### If you run into problems
### Try
```bash
  docker-compose down
  sudo systemctl restart docker
  export COMPOSE_HTTP_TIMEOUT=120
  export DOCKER_CLIENT_TIMEOUT=120
  docker-compose up 
```
