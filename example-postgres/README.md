# Description

This exemplifies a web admin interface that uses refine as a front-end and Genezio in the backend. It exposes some genezio classes as well as Genezio-based authentication. It uses a Postgres database for data storage.

You can play with it here: https://scarlet-male-mink.app.genez.io/

# Deploying this example

1. Clone this repository locally
2. `cd example-postgres`
3. Install genezio with `npm install -g genezio`
4. Deploy the project with `genezio deploy`
5. Go to `https://ABC-DEF-GHI.app.genez.io/`and test the project in your browser

If you want to test Genezio and Refine locally:

- Create a `.env` file in the `/server/` folder and save the database connection URL in the file as follows:

`DEMO_DATABASE_URL=postgresql://admin:<PASSWORD>@<POSTGRES_DOMAIN>/demo?sslmode=require`

You can get the postgres connection string form the genezio app / databases / select your database / connect

- run `genezio local` on the project root folder
