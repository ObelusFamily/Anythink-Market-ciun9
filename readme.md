# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup
To maker sure everything is working, first install [Docker](https://docs.docker.com/get-docker/)
After that, run the following command:

```bash
$ docker-v
$ docker-compose -v

```
If these commands don't work, please check the [Docker documentation](https://docs.docker.com/install/).
Otherwise, you can run the following command **from the project root directory**:

```bash
$ docker-compose up
```

Test this is working by going to the browser and typing `localhost:3000/api/ping` in the address bar.
