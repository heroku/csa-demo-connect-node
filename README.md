## Node Connect App
NodeJS Heroku Connect Sample

- Simple bootstrap node expressJS app.
- Establishes connection to Heroku Postgres.
- Queries a salesforce Heroku Connect Jobs Table.

Starting point for Salesforce/Heroku POC Demonstrations

#### Setting up your App

##### Heroku App
    1.) Create an app
    2.) Add Postgres Addon
    3.) Add Heroku Connect Addon
    4.) Set up a [free Salesforce developer account](https://developer.salesforce.com/signup)
    4.) Set up Heroku Connect Connection using the above account
    5.) From Heroku Connect Dashboard, add a Mapping for Account with the following fields:
     - account.name  
     - account.accountnumber
     - account.billingcity
     - accont.createddate
    6.) Link your app to this GitHub Repo
    7.) Deploy


#### Changing the Database Query
- Update Postgres query in [index.js](https://github.com/joeyjmorales/node-connect/blob/master/index.js)
- Update HTML temnplate in [index.ejs](https://github.com/joeyjmorales/node-connect/blob/master/app/views/index.ejs)
