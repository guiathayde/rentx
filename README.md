# rentx
<div align="center">
  <br />
  <img src="https://svgshare.com/i/Xp9.svg" alt="Logo RentX">
</div>
<h4 align="center">
  A car rental API, where you can save data to a Postgress database
</h4>

## API Routes /api-docs
![API Routes](https://i.imgur.com/nPY82gj.png)

## Code
![Code](https://i.imgur.com/UMiDqDI.png)

## 🧪 Tecnologies

This project was developed using cutting edge front-end technologies.

- [Express](https://expressjs.com/)
- [TypeScript](https://www.typescriptlang.org/)

## 🚀 Getting started

- You need to install [Node.js](https://nodejs.org/en/download/), [Yarn](https://yarnpkg.com/) and [Docker](https://www.docker.com/products/docker-desktop) to run this project.

**Clone the project and access the folder**

```bash
$ git clone https://github.com/guiathayde/rentx.git && cd rentx
```

**Follow the steps below**

- Copy the .env file and complete the informations
- Copy the ormconfig file and complete the informations

```bash
# Create the container of database with Docker
$ docker-compose up

# Install the dependencies
$ yarn

# Run the migrations of TypeORM
$ yarn typeorm migration:run

# Run the development environment
$ yarn dev

# Build the project
$ yarn build

# Run the production environment
$ node ./dist/shared/infra/http/server.js
```

<p align="center">Made with 💜 by Guilherme Athayde</p>
