# orm

## Install dependencies

```
npm install
```

### Local PostgreSQL database

```
docker-compose -up [--build] [-d]
```


```
npx sequelize init
```

Create Database called `orm_development`

```
npx sequelize model:generate --name User --attributes firstName:string,lastName:string,email:string
```