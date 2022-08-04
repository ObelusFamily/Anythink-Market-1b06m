# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

After installing docker, check if its set up properly on your machine by typing the following commands in your terminal : 
``` docker -v ```
  ```  docker-compose -v```

Set the project root directory you cloned from this github as your working directory on your terminal, and then run the command 
``` docker-compose up```
after this setup, you can test if the Backend is working properly by pointing your browser to [http://localhost:3000/api/ping](url)
As for the Frontend you can check if everyting is working properly on the linke [http://localhost:3001/register](url), where you'll need to register and create your password
