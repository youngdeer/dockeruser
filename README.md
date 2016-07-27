# dockeruser
use docker start webapp:
docker run --rm -it -p 3100:3000 --name dockerusetest -v "$(pwd)":/webapp -w /webapp node npm start

the follwing job is edit dockerfile to build images,then i can run this image in anywhere.
