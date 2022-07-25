# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. [Install docker.](https://docs.docker.com/get-docker/)
1. From TLD, run `docker compose up`.
1. Connect to localhost at http://localhost:3000/api/ping
1. Check backend connection via registering at: http://localhost:3000/register
