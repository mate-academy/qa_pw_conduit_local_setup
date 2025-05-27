# Conduit Example App

The Conduit real world example application uses Deno, Drash, Vue, Webpack, PostgreSQL, and Docker Compose.

## How to Run the application

### Docker Compose commands:

- For x86 chips run:

```bash
docker compose build && docker compose up
```

- For Apple silicon M-chips run:

```bash
docker compose -f docker-compose.m1.yml build && docker compose -f docker-compose.m1.yml up
```

## How to open application

Navigate to [http://localhost:1667](http://localhost:1667).

### `Make` commands

Alternativelly to above commands you can run the project with `Make` commands:

ARM processors: `make build-m1`, `make m1`
All other: `make build`, `make up`

Read more about make: [Unbuntu](https://www.unixmen.com/install-ubuntu-make-on-ubuntu-15-04/), [Windows](https://stackoverflow.com/questions/32127524/how-to-install-and-use-make-in-windows).

## Default users information

There are a total of 100 default users, with each user having the same password. Say we
want to login as user 32:

```text
Username: user32
Password: Userpass1
Email: user32@hotmail.com
```
