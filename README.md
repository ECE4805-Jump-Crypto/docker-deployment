# docker-deployment
## Setup environment
Clone the repository using ssh keys

```
git clone git@github.com:ECE4805-Jump-Crypto/docker-deployment.git
cd docker-deployment
```

## Install Docker
Install the latest version of Docker for your system from https://docs.docker.com/get-docker/

## Run Container
Use docker-compose to build and run image
```
docker-compose -f docker-compose.yml up -d --build
```

## Navigate to front-end
Front end is currently hosted locally at http://localhost:3000
