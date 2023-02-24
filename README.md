# docker-test

This repository is for docker test whit node.
1. dockerfile configuration (configuration for run image)
2. .dockerignore
3. server.js (server node for run in image)

#commands
docker run -p=5000:3000 --name=server1 dockertestnode (for execute image docker)
docker exec -it server1 bash (for execute docker in interactive mode by bash console)

in develop...
