# Ready Docker

Ready Docker is a macOS tool for starting then waiting for Docker.app to be ready. It is designed to be used in environments where you want to bring up a container without human interaction.

## Example Usage:

```bash
readydocker.sh && docker-compose up -d
```

## Expectations

- Docker should be located at /Applications/Docker.app
- /tmp/ should be writable
- docker command should be on $PATH

## Install

### Homebrew

```bash
brew tap camspiers/taps
brew install readydocker
```

### Manual

Download `readydocker.sh`, make it executable and ensure it is on your $PATH.
