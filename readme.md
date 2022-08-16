# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone the repo to your local machine.
2. Navigate to root directory of project.
3. Run "docker-compuse up" to load Anythink's backend and frontend.
4. Test backend by navigating to http://localhost:3000/api/ping
5. Test frontend by navigating to http://localhost:3001/register
