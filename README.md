# Church Calendar API

Browse Roman Catholic liturgical calendar through a web interface
or obtain it's data in JSON format through an API.

Original Repo from
[calendarium-romanum][caro] and
grape.

## Explore it on-line

Church Calendar API is a more or less RESTful read-only JSON API.

API documentation with URI examples and live links to API endpoints:
https://calendar-api.graceoftherosary.com/

## Running locally

1. install dependencies using Bundler
   `$ bundle install`
2. start application by `$ rackup`

## Running with Docker

This repository includes a `dockerfile` and a `docker-compose.yml`. You can run your own instance by running the following command from inside this folder:

`$ docker-compose up -d --build`

## Running specs

`$ rake test`

## Adding custom data

In order to add a new calendar:

1. put it's data file(s) in the `data` directory
2. create a new record in `config/calendars.yml`


## License

GNU/LGPL 3 or later
