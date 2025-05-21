# Deploying a Catalogi instance

This is a simple example of how to deploy a Catalogi instance, using Docker and Docker Compose.

## Requirements

- Docker
- Docker Compose

## Configure

First, create a `.env` file in the root of the project, with the following content:

## Keycloak Configuration

The deployment includes a pre-configured Keycloak instance with:

- A "catalogi" realm automatically loaded on startup
- Two pre-configured users:
  - Regular user: username `user`, password `password`
  - Admin user: username `admin`, password `admin`
- A pre-configured client for the Catalogi application