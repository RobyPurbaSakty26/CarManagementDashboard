```
npm seqielize-cli -g
```
npm init

npm install express

npm install --save sequelize

npm install --save pg pg-hstore

sequelize init

setting config => config.json

sequelize db:create

create table
sequelize model:generate --name Article --attributes title:string,body:text,approved:boolean

save model
sequelize db:migrate

add seeders
npx sequelize-cli seed:generate --name demo-user

add to db
sequelize-cli db:seed:all
