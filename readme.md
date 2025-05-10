# LiteLLM Compose Setup

Provides a Docker Compose setup for running LiteLLM.

## Getting Started

To get started with this project, you can use the following command to bring up the services in detached mode:

```bash
docker-compose up -d
```

## Configuration

Environment variables and other settings for the LiteLLM service are primarily managed in the following files:

- `config.yaml`: Contains specific configurations for LiteLLM.
- `docker-compose.yaml`: Defines the services, networks, and volumes, and can also include environment variables.

Refer to these files to customize your LiteLLM deployment.