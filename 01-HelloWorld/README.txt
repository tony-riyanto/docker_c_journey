https://stackoverflow.com/questions/58129302/how-to-pack-and-ship-a-simple-c-application-in-docker-without-the-gcc-compiler

# Build it
docker build . -t helloc


# Test it
C:\_learn\docker_c_journey\01-HelloWorld>docker run helloc
Hello World!
