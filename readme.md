# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

* Make sure you have `docker` and `docker-compose` installed on your machine.
* run `docker-compose up` from the project root directory to load Anythink's backend and frontend.
* If Docker is working correctly, the backend should be running and able to connect to your local database.
* Test this by pointing your browser to this [link](http://localhost:3000/api/ping)
* Try to open the user registration page and create a test user. Here’