# Starting up the Development Container

`cd client`

`docker build -t <dockeruser>/create-docker-workflow -f Dockerfile.dev .`

`docker run -p 3000:3000 <dockeruser>/create-docker-workflow`
