# Beszel Agent

This repository provides a ready-to-use `docker-compose.yml` for running the [beszel-agent](https://github.com/henrygd/beszel-agent) container.

## Usage

1. **Clone this repository**
2. **Create required folders for logs and data:**
   ```sh
   mkdir -p logs data
   ```
3. **Start the agent:**
   ```sh
   docker compose up -d
   ```

## Folder Structure

- `logs/` - Store logs from the agent or for your own use.
- `data/` - General purpose data storage for the agent or related services.

## Configuration

The `docker-compose.yml` mounts several host folders into the container for monitoring. Adjust the paths as needed for your environment.

## Security

The agent uses the provided SSH public key for authentication. Make sure to keep your keys secure.
