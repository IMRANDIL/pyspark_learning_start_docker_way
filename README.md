# PySpark Learning Environment

This repository sets up a **PySpark learning environment** with Docker, enabling you to experiment with Spark, Jupyter, and related tools effortlessly.

## Features

- **Apache Spark**: Distributed data processing.
- **JupyterLab**: Interactive notebooks for data exploration.
- **Delta Lake**: ACID transactions and time travel.
- **Python Libraries**: Pre-installed tools like Pandas, NumPy, and MLflow.
- **Dockerized Setup**: Easy-to-use, portable environment.

## Prerequisites

- [Docker](https://www.docker.com/) installed on your system.

## Quick Start

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/pyspark-learning.git
    cd pyspark-learning
    ```

2. Build and start the containers:
    ```bash
    docker-compose up --build
    ```

3. Access the services:
    - **Spark Master UI**: [http://localhost:8080](http://localhost:8080)
    - **JupyterLab**: [http://localhost:8888](http://localhost:8888)

## Project Structure

- `requirements.txt`: Python dependencies.
- `Dockerfile`: Custom JupyterLab image with PySpark.
- `docker-compose.yml`: Multi-container setup for Spark and Jupyter.

## Customization

- Modify `requirements.txt` to add/remove Python libraries.
- Adjust `docker-compose.yml` for resource allocation.

## License

This project is licensed under the [MIT License](LICENSE).

Happy learning! 🚀  