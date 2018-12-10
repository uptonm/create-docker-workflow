# Starting up Containers

## Run Development Server

`cd client`

`docker-compose up`

## Run Tests

`cd client`

`docker build -f Dockerfile.dev .`

`docker run -it <container_id> npm run test`

## Run Build

`cd client`

`docker build .`

`docker run -p 8080:80 <container_id>`
