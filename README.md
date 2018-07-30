# PHP7 Laravel 5.X + Docker

## Build Docker Image

Run the following command:

`docker build [FILE_PATH] -t [TAG_NAME]`

## Running the container

Run the following command

`docker run -d -p HOST_MACHINE_PORT:80 -v $PWD/[LARAVEL_APP]:/var/www  [TAG_NAME]:latest`
