# Conduit Example App

The Conduit real world example application uses Deno, Drash, Vue, Webpack, PostgreSQL, and Docker Compose.

## How to Run the application

### Docker Compose commands:

- For x86 chips run:

```bash
docker compose build && docker compose up
```

- For Apple silicon chips (M1, M2) run:

```bash
docker compose -f docker-compose.m1.yml build && docker compose -f docker-compose.m1.yml up
```

### `Make` commands

Alternativelly to above commands you can run the project with `Make` commands:

Apple M1, M2: `make build-m1`, `make m1`
All other: `make build`, `make up`

Read more about make: [Unbuntu](https://www.unixmen.com/install-ubuntu-make-on-ubuntu-15-04/), [Windows](https://stackoverflow.com/questions/32127524/how-to-install-and-use-make-in-windows).

## How to open application

Navigate to [http://localhost:1667](http://localhost:1667).

## The application built with

- [Docker](https://www.docker.com/) - Containerisation
- [Apache](https://httpd.apache.org/) - Acts as how Apache can be used as a
  proxy server for Drash
- [Deno](https://deno.land) - Javascript and Typescript runtime
- [Drash](https://drash.land/drash) - Web server
- [Vue](https://vuejs.org/) - Frontend framework
- [Webpack](https://webpack.js.org/) - Bundling Vue
- [Postgres](https://github.com/deno-postgres/deno-postgres) - Postgres driver
  for the applications database
- [Bcrypt](https://github.com/jamesbroadberry/deno-bcrypt/tree/master) - Hashing
  and comparing passwords
- [Rhum](https://github.com/drashland/rhum) - Testing framework
- [Dmm](https://github.com/drashland/dmm) - Module Manager for Deno to update
  our dependencies
- [Vue-input](https://www.npmjs.com/package/@johmun/vue-tags-input) - Library
  used to help the display of article tags as 'pills', allowing them to be
  removed and added like a shopping cart
- [Cypress](https://cypress.io/) - Browser testing framework

Drash codebase containing real world examples (CRUD, auth, advanced patterns, etc) that adheres to the [RealWorld](https://github.com/gothinkster/realworld-example-apps) spec and API.
