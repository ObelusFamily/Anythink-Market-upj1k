# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Start Docker
Run docker-compose up  from the root directory
Check that your backend is running, by visiting http://localhost:3000/api/ping
Then check your frontend is running and connected to the backend by visiting http://localhost:3001/register and creating a user.

Run docker exec to test scripts inside of your Docker containers, and you'll be ready to start!
