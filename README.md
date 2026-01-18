# Mattermost Docker Deployment

## Overview
Self-hosted Mattermost deployment using Docker Compose and Nginx.

## Prerequisites
- Docker
- Docker Compose
- Domain name
- TLS certificate

## Directory Structure
- docker-compose.yml
- nginx/
- mattermost/
- config/
- data/ (runtime, ignored)

## Usage
```bash
docker compose up -d

