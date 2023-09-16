docker build -t image_name

docker images

docker run -p 5000:3000 image_name

view contents of docker machine:

docker ps -> all containers running on machine

docker exec -it container_id /bin/bash
(like sshing into a machine)

docker kill container_id

layering in part2 of docker tutorial -> cached when running build once again

docker run -d -p 27018:27017 mongo and check in localhost:27018 in compass

docker image rm -f IMAGE
