# Kafka Setup on Railway

This repository contains the setup for deploying Zookeeper, Kafka, and Kafka UI on Railway using Docker.

## Structure
- `zookeeper/`: Zookeeper Docker configuration.
- `kafka/`: Kafka Docker configuration.
- `kafka-ui/`: Kafka UI Docker configuration.
- `docker-compose.yml`: For local development and testing.

## Deployment Instructions
1. Deploy `zookeeper/` to Railway as a separate service.
2. Deploy `kafka/` to Railway, linking it to the `zookeeper` service.
3. Deploy `kafka-ui/` to Railway, linking it to the `kafka` service.

## Access Kafka UI
Once deployed, access Kafka UI from the public Railway URL provided.
