# Intslall LEMP using Docker

You had to install Docker and Docker-Compose then you can follow the guide below.

## Project structure

- www - projects files
- mysql - db files
- logs - logs from images
- hosts - nginx configuration
- images - folder for our images

## How to start

Step 1. Input the code into terminal: 

`mkdir www www/hello.test mysql logs hosts && echo "<?php phpinfo();" > www/hello.test/index.php`

Step 2. Start docker: 

`docker-compose up -d`

Enjoy with docker :)

## How to manage different containers

Open terminal within the container:
`docker exec -i -t container_id /bin/bash`

