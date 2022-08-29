# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Download repo
2. Install Docker ([https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/))
3. Check that Docker is installed 
        docker -v
    and
        docker-compose -v
4. Navigate to the repo folder
5. Start the container in Docker:
        docker-compose up
6. Check that the app is running successfully: http://localhost:3000/api/ping
7. Check that the front end is working too by creating an account: http://localhost:3001/register

