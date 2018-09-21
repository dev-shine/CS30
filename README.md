## Getting started
1/ In folder `/server/src/config` rename file `config_example.js` to `config.js` and add your own settings


2/ Install docker and Prisma cli. (https://www.prisma.io/docs/tutorials/setup-prisma/create-new-db/mysql-gui4peul2u)


3/ In folder `/server`, run:
```sh
#init app
docker-compose up -d


#Deploy app
prisma deploy
```

4/ In 3 different terminals:


```sh
# Prisma: Graphql and mySql (port 4000)
cd server
yarn install
yarn start
```

```sh
# Media server: ExpressJs (port 8000)
cd express
yarn install
yarn start
```

```sh
# Frontend: ReactJs (port 3000)
cd react
yarn install
yarn start
```

Go to url: http://localhost:3000
