# Local Development Environment for Multiple PHP Versions of WordPress with phpMyAdmin

This repository provides a Docker Compose setup for running multiple versions of WordPress with different PHP versions (5.6, 7.0, 7.4, 8.2) along with a phpMyAdmin instance to manage the databases.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Docker](https://www.docker.com/products/docker-desktop)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Usage

1. Clone this repository to your local machine:

   ```sh
   git clone https://github.com/sajdoko/local-wp-docker.git
   cd local-wp-docker
   ```

2. Start the Docker containers:

    ```sh
    docker-compose up -d
    ```

3. Access each WordPress instances:

- PHP 5.6: <http://localhost:8051>
- PHP 7.0: <http://localhost:8052>
- PHP 7.4: <http://localhost:8053>
- PHP 8.2: <http://localhost:8054>

4. Access phpMyAdmin:

- <http://localhost:8050>

## Configuration

- Customize the `docker-compose.yml` file to adjust ports, environment variables, and any other settings to match your specific requirements.
