# Running the Ottr tech-stack

Ottr is made up of 4 parts, the database (ottr-db), the backend (ottr-api), the web-app (ottr-web) and the iOS app (ottr-ios).

For the API to work, it needs the database. For the iOS and Web apps to work, they need the api.

So the database is the first thing we need to setup.

Before you start install;
* NodeJS
* Chrome or Firefox (Ottr requires location permissions, which require SSL in Safari).
* DBeaver Community Edition

## Setting up the database.
Use docker. It's simple and i've written a blog post about how to do it [here](https://adamfallon.com/2020/07/08/postgres-in-docker/).

Once thats done, connect to it using [Dbeaver](https://dbeaver.io/).

Connect to or create a new database, then open a SQL Editor. Then paste in the SQL from [backup_scheme.sql](https://github.com/afallon02/ottr-db/blob/master/backup_schema.sql) and execute. You now have the Ottr Database.

## Running the API.
Download the ottr-api [here](https://github.com/afallon02/ottr-api).


Follow the instructions in the [README](https://github.com/afallon02/ottr-web/blob/master/README.md) to run.

## Running the web-app
Download the ottr-web application [here](https://github.com/afallon02/ottr-web) 

Follow the instructions in the [README](https://github.com/afallon02/ottr-web/blob/master/README.md) to run.

## (Optional) Running the iOS app.
Download ottr-ios [here](https://github.com/afallon02/ottr-ios)

Follow the instructions in the [README](https://github.com/afallon02/ottr-ios/blob/master/README.md) to run.

## Deploying to AWS
Instructions Coming Soon...