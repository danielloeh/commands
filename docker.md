## Docker

### Delete all containers
`docker rm $(docker ps -a -q)`

### Delete all images
`docker rmi $(docker images -q)`

### Pretty PS
docker ps --format "{{.ID}} - {{.Image}} - {{.Status}}" 
