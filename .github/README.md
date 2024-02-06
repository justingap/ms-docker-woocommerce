# MS WooCommerce for Docker

The purpose of this repo is to provide a containerised version of WooCommerce for quick and easy local development and testing.

**This container is not configured for use in a production environment and should never be deployed to a live site.**

## How to Install
1. Install Docker Desktop from the Managed Software Centre
2. Clone the repository to your local machine
    - Alternatively, create a new directory and download the docker-compose.yml into it
3. Make sure Docker Desktop is running
4. Navigate to the directory containing docker-compose.yml within your Terminal
    - If you need a quick review on navigating file systems with Terminal, [try this guide](https://terminalcheatsheet.com/guides/navigate-terminal#navigating-folders)
5. Run the command `docker compose up -d`
6. Once your Terminal has finished the job (look for check marks), return to Docker Desktop and look at Containers
7. You should have a new Container listed with a green icon
8. If the container is running, your new Wordpress store should be available at [localhost:80](http://localhost:80)

Below image demonstrates what Docker may look like when the containers are running successfully.
[Screenshot of Docker with running containers for a mariadb database, and a wordpress service](/img/Docker-Containers-Running.png)

## Stopping the Container
1. If you don't need the environment any more, you can safely stop the container (click the Stop button on the parent).
[Screenshot of Docker containers, with a red circle around a Stop button](/img/Docker-Stop.png)

2. This effectively shuts down the 'server'.