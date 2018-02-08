## Compilar Dockerfile

´´´
docker build -t jenkins-docker .
´´´

## Ejecutar imagen

´´´
docker run -d -p 8080:8080 -v /var/run/docker.sock:/var/run/docker.sock --name jenkins jenkins-docker
´´´