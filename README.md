# Getting Started with Docker-Compose

This project was created to use docker-compose to spin off wordpress and mysql

## Available Scripts

In the project directory, after cloning and installing docker-compose, you can run the following:

### `sudo docker-compose up -d` to start the containers in the docker-compose in the background
### `sudo docker-compose ps` to inspect the containers running in the docker-compose


Once up it runs a wordpress websites
Open [http://localhost:8089] to view in your browser.


To stop the running servers , use this:
### `sudo docker-compose stop`

To bring down the containers, use this:
### `sudo docker-compose down`

To view the network:
### `sudo docker network ls`

To inspect the network:
### `sudo docker inspect {Newtork Name}`
