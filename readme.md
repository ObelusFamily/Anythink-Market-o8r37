# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Steps To setup environment:

    1. Clone the repo: `git clone https://github.com/ObelusFamily/Anythink-Market-o8r37.git`
    2. Change to the directory: `cd Anythink-Market-o8r37`
    3. Run `docker-compose up -d`
    4. Open the browser and go to  http://localhost:3000/api/ping to see whether the backend is running.
    5. You should see the app running
    6. If you want to test the frontend, open the browser and go to http://localhost:3001/register to see whether the frontend is running.
