# Docker-Like Tool in Python

This project is a lightweight tool written in Python that emulates basic Docker functionality. It provides filesystem and process isolation, as well as the ability to fetch images from Docker Hub.

## Setup

### Requirements

- Python 3.6 or later
- Docker installed locally (for testing)

### Installation

1. Clone the repository:
   
   git clone https://github.com/enurce26/buildyourowndocker.git

2. Install the required Python packages:
   
    pip install -r requirements.txt

3. Ensure Docker is installed and running:

    docker --version



### Usage

To use PyDock, run the following command:
python main.py <image_name> <command> [arguments]
