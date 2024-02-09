# survey-nodejs

Survey application with Nodejs - Fastify - Prisma

# Project

Event NLW Expert (Node.js)

A real-time voting system where users can create a poll and other users can cast their votes. The system generates a ranking among the options and updates the votes in real time.

## Requisites

- Docker;
- Node.js;

## Setup

- Clone the repository;
- Install dependencies (`npm install`);
- Setup PostgreSQL and Redis (`docker compose up -d`);
- Copy `.env.example` file (`cp .env.example .env`);
- Run application (`npm run dev`);
- Test it! (I personally recommend testing with [Hoppscotch](https://hoppscotch.io/)).

## Start project

```bash
yarn dev

# Or

npm run dev
```
