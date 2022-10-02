# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone this repository.
2. [Install Docker](https://docs.docker.com/get-docker/) if you haven't done so already.
  - You can verify that it's installed properly by running `docker -v` or `docker-compose -v`.
3. From the root directory, run `docker-compose up`.

### If you wish to verify that everything's working:
- Verify that the backend is working correctly by going to http://localhost:3000/api/ping.
- Verify that the frontend is connected to the backend by going to http://localhost:3001/register and creating a new user.
