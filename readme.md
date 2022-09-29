# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone the repo to your local machine
2. Install docker and verify it's working by running `docker-compose -v`
3. Run `docker-compose up` on the root directory of the repo
4. Navigate to [http://localhost:3000/api/ping] to check if the backend is working
5. Navigate to [http://localhost:3001/register] to verify the frontend is working
6. You're ready!