# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone to local machine: `git clone https://github.com/ObelusFamily/Anythink-Market-81yrl`
2. Install Docker. Confirm installation by running commands `docker -v` and `dock-compose -v`.
3. Spin up the application by running `docker-compose up` from the base app directory.
4. Confirm the backend and frontend are up and running. Point browser to `http://localhost:3000/api/ping` and confirm 200 response. Poinbt browser to `http://localhost:3001/` and register a new user.

