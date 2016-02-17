# Public Company Website

To build:

* ./buildDockerImage.sh

To run first remove any existing company-wordpress docker container, as the base Wordpress docker image copies the Wordpress directories containing the theme on first run:

* docker ps -a
* docker rm [CONTAINER ID]

Now run the containers:

* docker-compose up
 
