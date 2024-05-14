# Microservices system project 

## Getting Started

### Prerequisites

Make sure you have the following prerequisites installed on your machine:

- Docker
- Docker Compose

## Setup

To use the project you will first need to set up the chat-ui microservice. To do that, in the `chat-ui` folder edit the `.env` file. Inside you need to specify the following arguments:
```
MONGODB_URL=mongodb://mongo-chatui:27017
HF_TOKEN=<your access token>
```
You can get your own huggingface access token from [your own Hugging Face profile](https://huggingface.co/settings/tokens).

## Usage

Start the project and its dependencies using Docker Compose:

```bash
docker-compose up -d
```

Visit [http://localhost:3000](http://localhost:3000) in your browser to access the project.


## Stop and Cleanup

To stop the containers and remove the network:

```bash
docker-compose down
```
