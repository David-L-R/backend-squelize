# backend-squelize

## Commands
```
// Create a new model
$ model:generate --name user --attributes name:string,email:string,phone:integer,password:string

// Migrate
$ npx sequelize-cli db:migrate

// Create seeds
$ npx sequelize-cli seed:generate --name some-users

// Seed all
$ npx sequelize-cli db:seed:all

// To un-do the seed we can use
$ npx sequelize-cli db:seed:undo:all

// We can also point to a specific seed file to run instead of "all" using the --seed flag
$ npx sequelize-cli db:seed --seed <file_name>
$ npx sequelize-cli db:seed:undo --seed <file_name><extension>

// Rerun everything when errors occur
$ npx sequelize-cli db:migrate:undo:all
$ npx sequelize-cli db:migrate
$ npx sequelize-cli db:seed:all

```
