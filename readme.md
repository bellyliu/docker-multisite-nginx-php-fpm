# dockerized multiple site for nginx php-fpm
- its has 2 sites
    * php-docker.local
    * php-docker-2.local

- exposed on port 8080

- it has custom 404 page

# How to
- clone this repository
- cd to the directory
- execute ```docker-compose up```
- on your browser open 
    * php-docker.local:8080
    * php-docker-2.local:8080