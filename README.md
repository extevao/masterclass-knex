


npx knex init


// MIGRATIONS
npx knex migrate:make create_table_users
npx knex migrate:latest

// SEEDS
npx knex seed:make 001_users
npx knex seed:run
