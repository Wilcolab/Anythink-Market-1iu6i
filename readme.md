# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
### 1. Clone this repo
Use the `git clone` command.
### 2. Install Docker
- [Get Docker](https://docs.docker.com/get-docker/) and follow the instructions to set it up.
- Verify docker is ready by running the following commands in your terminal: `docker -v` and `docker-compose -v`.
### 2. Start Anything 
- Run `docker-compose up` from the project root directory to load Anythink's backend and frontend.
- If Docker is working correctly, the backend should be running and able to connect to your local database.
### 3. Test Your Installation
- Open [http://localhost:3000/api/ping](http://localhost:3000/api/ping) in your browser
- Open the user registration page and create a test user [http://localhost:3001/register](http://localhost:3001/register)
### 4. Done
Good job, your environment is ready!
