# How to build this app locally
----------

* Clone this repo locally git clone <utl>
* Go to the package folder and run the docker build command
  - `docker build -t demo-app:1.0`
* Verify the `my-app` docker image with the tag as `1.0` is created using `docker images` command
* Build the docker containers using the docker-compose.yaml file
  - `docker-compose -f docker-compose.yaml up`
* To clean up: `docker-compose -f docker-compose.yaml down`
