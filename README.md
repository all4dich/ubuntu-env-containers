# Ubuntu Development Environment using Docker

This repository provides a Dockerized Ubuntu environment for development purposes. It allows you to have a consistent and isolated development environment using Docker containers.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

*   [Docker](https://docs.docker.com/get-docker/)
*   [Docker Compose](https://docs.docker.com/compose/install/)

### Installing

1.  Clone the repository:
    ```bash
    git clone https://github.com/your-username/ubuntu-env-containers.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd ubuntu-env-containers
    ```
3.  Build and start the Docker container:
    ```bash
    docker-compose up -d
    ```

## Usage

To access the running container:
```bash
docker-compose exec ubuntu_2204 bash
```

The `workspace` directory in this repository is mounted as a volume in the container at `/workspace`. You can place your project files in this directory to have them accessible within the container.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
