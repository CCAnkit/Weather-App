# Weather-App


#### Backend TeckStacks 
- NodeJS
- Express
- MongoDB
- JavaScript
- 


#### Frontend TechStacks
- HTML
- CSS
- Basic React
- Postman for Testing

#### Packages
- express
- body-parser
- mongoose
- cors
- dotenv
- nodemon
- axios


#### Goals
- Quick and easy to get the Weather.
- Anyone can get the weather Information.
- It takes Less Time and Space Complexity.


#### Weather API's
- 1. GET Request - statically get the weather data from the weather api
- 2. POST Request - dynamically get the weather data based on request body
- 3. POST Request - get the weather data from the api, save it to mongo, then return the data back
- 4. GET Request - get the weather data saved from Mongo


#### EndPoint 

- 1) /weather
   method GET

- 2) /weather
   method POST

- 3) /weatherMongo
   method POST

- 4) /weatherMongo
   method GET
   
   
#### Feature and Mapper
- 1. Current Mapper
   const mapperCurrent = {
    name: "town",
    region: "state",
    country: "Nation",
    lat: "latitude",
    lon: "longitude",
    tz_id: "Time Zone",
    localtime: "Time"
   }

- 2. Forecast Mapper
   const mapperForecast = {
    sunrise: "Dawn",
    sunset: "Dusk",
    moonrise: "moonlit",
    moonset: "moonsleep",
    moon_phase: "orientation",
    moon_illumination: "Illumination"
   }
