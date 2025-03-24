# NGINX Fluentd Docker Compose Demo

This demo showcases the integration of NGINX and Fluentd using Docker Compose. The solution demonstrates:

- A **NGINX** container serving as a web server.
- A **Fluentd** container collecting logs from NGINX.
- A custom **network setup** to allow seamless inter-container communication.

## How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/Aadik1ng/NGINX-with-Logging.git
    cd nginx-fluentd-demo
    ```

2. Build and start the containers using Docker Compose:
    ```bash
    docker-compose up
    ```

3. Access the NGINX container's logs through Fluentd.

## Why Fluentd?

Fluentd is a flexible log collector that integrates seamlessly with Docker and provides powerful log processing capabilities.
