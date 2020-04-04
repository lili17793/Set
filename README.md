# SET

Welcome!


## Installation
### back folder
#### Install node modules
```
npm i
```

#### Run mysql
```
docker run --name mysql-set --restart unless-stopped -e MYSQL_DATABASE=set -e MYSQL_USER=set -e MYSQL_PASSWORD=set -e MYSQL_ROOT_PASSWORD=root -p 3310:3306 -d mysql:5.7
```

#### Run migrations
```
npx run migrate
```

#### Run seeds to generate the cards
```
npm run seed
```

#### Start back
```
npm start
```

-------

### front folder
#### Install node modules
```
npm i
```

#### Start front
```
npm start
```
