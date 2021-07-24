# Rails Template with Docker 

Ruby on rails development Environment.

## Docker

To build:

- run `docker compose build`

To run:

- run `docker compose run --rm --service-ports ruby_dev`

To run in multiple terminal windows:

- run `docker exec -it YOUR_CONTAINER_ID /bin/bash`

To exit bash or your container:

- run `exit`

To cleanup:

- run `docker compose down`

## Rails

To start a new project:

- run `rails new <app-name>` then `cd <app-name>`

- Install bundles. run `bundle update && bundle install`

Starting the server:

- run `rails server -p $PORT -b 0.0.0.0`. Check your [localhost:3000](http://localhost:3000) to see if it's working.

Stopping the server:

- hit `ctrl-c` on your keyboard to stop the server.
