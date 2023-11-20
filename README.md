## Description

Boilerplate for Nest auth

## Installation

```bash
$ yarn install
```

## Database

Run docker for postgress database

```bash
$ docker compose up dev-db -d

or

$ yarn db:dev:up
```

## Prisma

Studio

```bash
$ npx prisma studio
```

## Running the app

```bash
# development
$ yarn run start

# watch mode
$ yarn run start:dev

# production mode
$ yarn run start:prod
```

## Test

```bash
# unit tests
$ yarn run test

# e2e tests
$ yarn run test:e2e

# test coverage
$ yarn run test:cov
```
