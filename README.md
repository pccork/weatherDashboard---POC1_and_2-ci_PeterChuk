
# weather dashboard


Assignment HDip in Computer Science Web Development 1, SETU



## Authors

- [@pccork](https://www.github.com/pccork) peter chuk



## project description
# Weather App Proof of Concept (POC)

This proof of concept (POC) demonstrates the functionality of a weather app according to the provided specifications. The app is designed to display hourly weather forecasts for the next 7 days and allow users to customize their dashboard by choosing preferred weather parameters such as temperature, relative humidity, wind speed, etc.

## Features

- Display hourly weather forecasts for the next 7 days.
- Customize dashboard preferences for weather parameters.
- Retrieve weather data from the provided weather data file.

## installation

To run this proof of concept, follow these steps:
enter the web page URL to any web browser; then
click the forecast button at the bottom of each city box in the dashboard page.  The city focus page will display the weather at present hour and 7 days temperature forecast.

## Roadmap

- continues developing the dashboard to allow full integrations of the dashboard page under the JavaScript layer structure with component based design for better code understanding, improved future upgrade and maintenance.

- Add and develop the prefernce page to allow users to customise what weather parameters to display in the city focus page. 

## Usage/Examples

```javascript
import Component from 'my-project'
//Adapting codes created by lecture John Rellis

/
//allow the selction of cities
document.addEventListener("DOMContentLoaded", () => {
            const urlParams = new URLSearchParams(window.location.search);
            const currentCity = urlParams.get('city');

 //Settup up date and time object based on real time is an important aspect of this assignement
 const now = dayjs(); // create a new date object that represents this time
            
const currentHour = now.hour(); // 0 - 23 as a number

// indexOfCurrentHour is created to query a specific array element in the dataset in JASON  

const indexOfCurrentHour = hourlyData.time.indexOf(`TodayT${currentHour}:00`);

//setup weather and weather codes 7 days  using data from datastore
const hourlyWeatherCode = hourlyData.weather_code[indexOfCurrentHour];


## Documentation

CSS framework: bulma

https://cdn.jsdelivr.net/npm/bulma@0.9.4/css/bulma.min.css

Site generator
Elevently 
For more information please visit:
https://v2-0-0.11ty.dev/docs/


time and date library
https://cdn.jsdelivr.net/npm/dayjs@1/dayjs.min.js


For latest documentation of the weather_data.js weather dataset, please visit:
Open-Meteo.com


## Contributing

Contributions to this project are well come please see below for contact information.



## contact information
20108887@mail.wit.ie

## Acknowledgements

codes in this project is based on lectures and labs created and run by my lecture John Rellis in SETU.


