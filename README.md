# Test task for MEVN stack

Project consists of two directories: api and frontend

# API

Api is build with express and mongoose and uses [swagger-jsdoc](https://www.npmjs.com/package/swagger-jsdoc) for generating Swagger documentation from commentaries in code.

## Getting Started

To get API server running locally:

- Install NodeJS ([instructions](https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions-enterprise-linux-fedora-and-snap-packages))
- Install MongoDB Community Edition ([instructions](https://docs.mongodb.com/manual/installation/#tutorials)) and run it by executing `mongod`
- Go to api folder `cd api`
- Install required dependencies `npm install`
- `npm start` to run the local server

After that you will see message saying that API is up on port 3000. You can also find full Swagger docs at http://localhost:3000/docs.

Optionally:

- `npm docs` to generate new swagger.json from commentaries in code.
- change config.js up to your needs

# Frontend

Frontend is build on Vue with help of vue-cli. It was my first Vue project so I needed some boilerplate code to start with and build it in one day. It also uses bootstrap 4 for some styling.

## Getting started

First of all go to frontend folder: `cd frontend` and install dependensies: `npm install`

Then:

- Run in dev mode: `npm run dev`
- Build production version: `npm run build`
- Start local example with builded production version: `npm start`

## To do

1. Add validation
2. Write smaller components for frontend
3. Write tests for API
