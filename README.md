## Getting started


In folder `/server`, run:
```sh
#init app
docker-compose up -d


#Deploy app
prisma deploy
```

In 3 different terminals:


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
```sh
# TimeLine
Task1 : 9.20 / 8.50 - 9.20 / 10
Task2 : 9.21 / 10.30 - 9.21 / 11.20
```
Go to url: http://localhost:3000
