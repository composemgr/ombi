# Ombi

A self-hosted application for managing ombi.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/ombi/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/ombi" ~/.local/srv/docker/ombi
cd ~/.local/srv/docker/ombi
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install ombi
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
