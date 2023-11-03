# django-docker
django-postgresql-nginx loadbalancer with docker-compose
Install Docker engine from main documentation on your os : https://docs.docker.com/engine/install/
Make sure docker compose is installed.
Based on Ubuntu 22.04LTS Server :
  Create directory for your docker configuration: mkdir -p /home/docker
  cd /home/docker
  git https://github.com/vahidirp/django-docker.git
You should change "stack" and replace with your application or website name.
Also enter the enviroment for database-server on docker-compose.yml
To run : docker compose up 
 check logs if no errors : ctrl+x 
 docker compose up -d
Check your service up or down or restarting with : " docker ps " or " docker container ls "
