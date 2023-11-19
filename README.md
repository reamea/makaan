# makaan 0.0.3
This is public repo for makaan with docker file to build image from debian apache2 and expose 80.

# first commit from laptop

# Dockerize
    docker build -t makaan:0.0.3 .
    docker run -d -p 80:80 makaan:0.0.3
    open url: localhost:80
# Push to docker hub
    docker tag makaan reamea/makaan:0.0.3
    docker login
    docker push reamea/makaan:0.0.3