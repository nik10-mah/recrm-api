# recrm-api
Real Estate CMR Backend API in Node JS with Express JS

## Installation Steps
 - `git clone https://github.com/nik10-mah/recrm-api.git` or `git clone git@github.com:nik10-mah/recrm-api.git`
 - `cd recrm-api`
 - create an **.env** file as mentioned below
 - `npm install` or `yarn install`
 - `npm start` will start the project in 5001 port on localhost or 127.0.0.1 


### Creating an environement file
Create a **.env** file in root of the project with following mongo db connection url **DB_URL**, **DB** name , stripe api key **STRIPE_PRIVATE_KEY** and  **CLIENT_URL** where frotnend for this app will run
```
DB_URL=mongodb://localhost:27017
DB=REALESTATECRM
STRIPE_PRIVATE_KEY=
CLIENT_URL=http://localhost:3000/
```

## Deploymemnt
To run the app on VM linux server, just install **pm2** tool and run `PORT=4000 pm2 start npm --name "recrm-api" index.js` in project root. Project will run on **127.0.0.1:4000**
