https://stackoverflow.com/questions/58129302/how-to-pack-and-ship-a-simple-c-application-in-docker-without-the-gcc-compiler

docker build . -t helloc

Lessons learnt :

1) The default volumes are in :
\\wsl$\docker-desktop-data\data\docker\volumes\01-helloworld_myapp

2) Do not use the volumes in Dockerfile, use it hn the docker-compose

3) Use bind mount syntax (see docker-compose) to define ad hoc folder below the current folder

