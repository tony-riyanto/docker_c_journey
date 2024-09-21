# use alpine as base image
FROM alpine AS build-env
# install build-base meta package inside build-env container
RUN apk add --no-cache build-base
# change directory to /app
WORKDIR /app
# copy all files from current directory inside the build-env container
COPY . .
# Compile the source code and generate hello binary executable file
RUN gcc -o hello helloworld.c

# at last run the program
CMD ["hello"] 
