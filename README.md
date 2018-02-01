# docker-multistage-nginx-express

## Setup

```bash
# Install Yarn https://yarnpkg.com/en/docs/install
# Install Docker https://www.docker.com/get-docker
brew install yarn
brew cask install docker
./setup
```

## Develop

```bash
# start developing 🎉
./ops start

# stop developing 🍺
./ops stop
```

## Test

```bash
# no tests yet
```

## Build

```bash
./ops build
```

## Deploy

```bash
# Wait for Docker Cloud build to finish before shipping
./ops ship [stage | prod]
```
