# docker-deployment
## Setup environment
Clone the repository using ssh keys

```
$ git clone git@github.com:ECE4805-Jump-Crypto/docker-deployment.git
$ cd docker-deployment
```

## Install Docker
Install the latest version of Docker for your system from https://docs.docker.com/get-docker/

## Install Node.js
Install the current version of Node.js from https://nodejs.org/en/

## Run Container
Use docker-compose to build and run image
```
$ docker-compose -f docker-compose.yml up -d --build
```

## Navigate to front-end
Front end is currently hosted locally at http://localhost:3000

## Stop Application
Run the following command to stop the application from running
```
$ docker-compose stop
```

## API & MongoDB Atlas Account information
API that stores the added noeds: http://localhost:3000/api/v1/hotspots

## MongoDB Atlas 
Account: 13982106768@163.com
Password: Peiyqbb0504
Click Browse collection to see the added nodes information 
