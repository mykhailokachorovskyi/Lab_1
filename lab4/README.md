1. Read about Docker
***
2. Check Docker install by command sudo docker -v sudo docker -h sudo docker run docker/whalesay cowsay Docker is fun and redirect to my_work.log
***
3. Read Docker documentation
***
4. Create image w/ Django site which site create in previous lab by this commands: docker pull python:3.8-slim docker images docker inspect python:3.8-slim
***
5. Link repo Docker
***
6. sudo docker build -t laforp:django . sudo docker push laforp/lab4:django
***
7. Run docker image sudo docker run -it --net=host --rm -p 8000:8000 laforp/lab4:django
***
8. Build Dockerfile.site image sudo docker build -f Dockerfile.site -t laforp/lab4:monitoring . and push it to Docker sudo docker push laforp/lab4:monitoring
