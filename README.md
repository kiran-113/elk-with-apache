# docker-elk
Basic ELK stack in Docker


Now we can test our setup. One Apache (httpd) container is already started by using Docker-compose. Users of Docker Desktop for Mac should edit the gelf-address in the docker-compose.yml to udp://host.docker.internal:12201. Check here for more information. Don’t forget to update your environment by running docker-compose up -d again.
