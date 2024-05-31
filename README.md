# Dockerized Postgres with Docker-Compose

## Overview

This project dockerizes Postgres using Docker Compose on Ubuntu. It provides a seamless setup for managing Postgres instances within containers.

## Getting Started

### Prerequisites

- Ubuntu OS
- Docker
- Docker Compose

### Installation

1. Execute the `install-docker.sh` script to install Docker and Docker Compose:

   ```bash
   bash ./install-docker.sh
   ```

### Configuration

1. Navigate to the `./postgres` directory.
2. Update the `.env` file to set the Postgres password, port, and pgAdmin user credentials.

### Deployment

1. Navigate to the `./postgres` directory.
2. Execute the following command to deploy the Postgres
   instance:

   ```bash
   docker-compose up -d
   ```

## Usage

Once deployed, you can access pgAdmin at `[host IP]/pgadmin` and Postgres at `[host IP]:[PORT from .env]`.

## Troubleshooting

- If you encounter any issues during installation or deployment, refer to the Docker documentation or open an issue on this repository.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your enhancements.

## License

This project is licensed under the [MIT License](LICENSE).
