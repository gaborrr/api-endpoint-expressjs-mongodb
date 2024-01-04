## API endpoint with Express and mongoDB
Part 1 of 2 application API endpoint with Express and mongoDB  http://localhost:3001/
Part 2 is getting the data from this API and display it in react components. 
    http://localhost:3000/
    link to repository: 

Mongo DB 
database: "profile"
colleciton: "profiledata"

example JSON file to import to Mongodb ./example/profile.profiledata.json

Steps to setup on local environment
- use npm install
- add .env file in root folder
- add below line in .env file with your own connectionstring
MONGODB_URI = "mongodb+srv://<username>:<pass>@cluster0..."

- npm start
- open browser http://localhost:3001/

--------------------------------------------------------------------------------------------------
