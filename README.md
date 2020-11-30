# API
Making my own api just for fun

https://rapidapi.com/blog/nodejs-express-rest-api-example/#installation

GET https://www.ourapi.com/api/v1/stats/101 – This will get the stats for player 101
POST https://www.ourapi.com/api/v1/stats – This will create the stats a player
PUT https://www.ourapi.com/api/v1/stats/101 – This will update the stats for player 101
DELETE https://www.ourapi.com/api/v1/stats/101 – This will delete the stats for player 101

Each record will contain:
    an id of the Football player
    wins
    losses
    points scored

Since this is a training example, we will store all entries in a JSON file. In a real-world application, we would probably use a database instead. 
    Create a folder called routes
    Create a file called stats.json
    Create a file called stats.js