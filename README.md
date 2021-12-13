# Claidroid Internship Project

Summary - 

The web app accomplishes the following functions

1) Tracks disease outbreaks around the world
2) Informs users of travel restrictions in countries they plan on travelling to
3) Informs users of vaccinations they need to get to travel to a particular country
4) Allows them to store their vaccination record
5) Allows users to book flight tickets

# Deliverables

We have split the development of this product into clear stages. 

## Stage 1
### Deliverable 1:

Design Details: [Here](https://github.com/17Ayaan28/Claidroid_Internship_Project/blob/main/Reports/DESIGN_DETAILS.pdf)


### Deliverable 2:

#### API Documentation

Swagger: [Here](https://app.swaggerhub.com/apis-docs/z5158415/API-200OK/1.0.0-oas3#/)

API URL: http://australia-southeast1-seng3011-306108.cloudfunctions.net/

#### Logs

https://australia-southeast1-seng3011-306108.cloudfunctions.net/nlogs (The default number of logs returned is 10)

Alternatively you could specify the number of logs returned: 
 
e.g. https://australia-southeast1-seng3011-306108.cloudfunctions.net/nlogs?limit=20

#### Scraper
The combined branch contains the pure scraper code, which can be run locally and generates json file.

The scraper that connected to database can be found in main branch.

The scraper that need to be perically run is deployed ini cloud function and can be found in GCP_function_code in main branch.


## Stage 2
### Deliverable 3:
Demo and High-fi prototype of the web app, Destinated.

Created using ReactJS and hosted locally through npm.

Included all the basic but incomplete functalities due for the final presentation of web-app (except travel restrictions page).

### Deliverable 4:
Completed web-app Destinated along with Final report.

Frontend created using ReactJS and hosted on GCP. Firebase Realtime Database used for instant retrieval of users personal data.
Destinated includes the following functionalities : User authentication, Vaccination requirements and advice for all countries around the globe, disease outbreaks news for countries, Travel restrictions to a country, Personalised vaccination history, uploading vaccination details, Dyanmic current flight routes and flight registeration, Passenger details of registered travelers (visible only to airport staff).

API's used on web-app:
  1. EventS4fe API for outbreaks News: [Here](https://events4fe.herokuapp.com/swagger/)
  2. Lufthansa Open API to get schedules flights: [Here](https://developer.lufthansa.com/docs)
  3. Airport info API for IATA information: [Here](https://rapidapi.com/Active-api/api/airport-info) 
  4. AeroDataBox API for autosuggestion of list of Airports: [Here](https://www.aerodatabox.com/) 

Website is accessbile for smart phone users as well as desktop users at: [Here](https://seng3011-306108.web.app)


