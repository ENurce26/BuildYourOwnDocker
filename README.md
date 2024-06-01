Docker-Like Tool in Python

This project is a lightweight tool written in Python that emulates basic Docker functionality. It provides filesystem and process isolation, as well as the ability to fetch images from Docker Hub.
Setup
Requirements

    Python 3.6 or later
    Docker installed locally (for testing)

Installation

    Clone the repository:

    bash

git clone https://github.com/your-username/your-repository.git

Install the required Python packages:

bash

pip install -r requirements.txt

Ensure Docker is installed and running:

bash

    docker --version

Usage
Running the Tool

To use the tool, run the following command:

bash

python your_docker.py <image_name> <command> [arguments]

Replace <image_name> with the name of the Docker image you want to use and <command> with the command you want to execute inside the container. Additional arguments can be passed as needed.
Example

bash

python your_docker.py alpine:latest /bin/echo "Hello, World!"

Configuration
codecrafters.yml

The codecrafters.yml file contains configuration for the CodeCrafters platform, allowing you to test your Docker-like tool in their environment. It includes setup and test instructions.
Dockerfile

The Dockerfile contains instructions for building the Docker image used by your tool. It specifies the base image and any dependencies needed for your tool to run.
your_docker.sh

The your_docker.sh script is the entry point for your Docker-like tool. It sets up filesystem and process isolation and executes the specified command inside the container.
License

This project is licensed under the MIT License. See the LICENSE file for details.
