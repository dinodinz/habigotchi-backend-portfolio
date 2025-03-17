
## Habigotchi Backend

Backend server created for a Habit tracking mobile app, this database is hosting categories,pets,users and habits using a relational table setup hosted on supabase and render.

## Minimum required versions:

Node.js = v23.3.0
PSQL = 14.14

## 🛠 Tech Stack
- **Node.js** (v23.3.0)
- **Express.js**
- **PostgreSQL** (14.14)
- **pg & pg-format** (for database interaction)
- **Jest, Jest Sorted, Supertest** (for testing)
- **Nodemon**
- **Husky** (additional layer of testing)

## Instructions:

For anyone cloning this repo, since the environment files are added on the gitignore list, then you will not have a copy of them on your local machine.

You will need to add them manually to connect the dev and test detabases when working on the project.

You can add two new files named ".env.test" and ".env.development" on the root level of your repo directory and add their respective contents which are shown below.

.env.test: PGDATABASE=nc_news_test

.env.development: PGDATABASE=nc_news

## API endpoints hosted on Render:

Endpoint: https://habigotchi-server.onrender.com

Instructions: Add the api path after .com when testing

Example: https://habigotchi-server.onrender.com/api/categories

NOTE: API paths are availble in the endpoints.json file

## Summary:

This is a Habit Tracking mobile app, with pet integration. You finish your habits and get rewarded by coins which you can buy food to increase your pets health and happines as it decrements overtime. The concept is straight forward, you need to take care of your pet by doing all your habits on a daily or weekly basis.

## Dependencies

You will need to install the minimum dependency versions shown on the package.json file to avoid any issues when running the app

If you have installed recent versions and are having issues, then installing the exact versions would be the best option.

To do this you need to use "npm ci" instead of "npm i" as this will install the exact versions on the package.json file.

## Setup on your local machine

1.) Go here https://github.com/dinodinz/habigotchi-backend-portfolio

2.) Grab the HTTPS URL by clicking the green button "<> Code"

3.) Go to your machine terminal and run "git clone CODE_URL_HERE"

4.) Open the directory inside your IDE

5.) Run "npm ci" on your terminal to install the exact versions of all dependencies on the package.json file

6.) Create DEV and TEST databases by running "npm run setup-dbs"

7.) Seed DEV database by running "npm run seed"

8.)You can now do some testing by running "npm test"

## Important:
In order for the whole setup to work, you need to have the .env.test and .env.development files created which was stated at the beggining of this guide.
