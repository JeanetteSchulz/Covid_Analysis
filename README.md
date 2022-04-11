
<div align="center">
<img width= "100" img src="https://cdn.pixabay.com/photo/2020/04/25/02/03/coronavirus-structure-5089224_960_720.png" align="absbottom">
</br>
<img width= "300" src="https://covidactnow.org/static/media/covid-act-now-logo-url-dark.88f99a5f.png" alt="Covid Act Now Logo">

# README

### by Jeanette Schulz

</div align="center">
    
<hr style="border:2px solid blue"> </hr>

## Project Goals

As year two of this pandemic passes, I am taking a personal interest in studying the number of covid cases to see if data can tell me when this might be over. I am still diligently wearing a N95 these days, but that doesn't mean I don't dream of the day I can sit in a restaurant unmasked again AND feel safe. I would also like to possibly find some data on the 1918 Flu and possibly compare the two pandemics.

## Project Description

Covid Act Now is the COVID-focused U.S initiative of Act Now Coalition. Launched in April 2020, thier COVID data and risk assessment includes every U.S. state, 380+ metros, 3,100+ counties, and two U.S. territories.
They have served over tens of millions of users since the beginning of the pandemic, and keep more than 200k subscribers up to date on COVID news and alerts.
They've supported hundreds of federal, state, and county officials as well as numerous multinational corporations and NGOs to develop data-driven COVID responses.
Using thier API, I can access this data to dive into the numbers and see if there is a downward trend that may allow us to stop wearing masks soon.


## The Plan

**Plan - Acquire - Prepare - Explore - Deliver**

- Wrangle
    - Register for an API key [here](https://apidocs.covidactnow.org/).
    - Acquire data from [Covid Act Now](https://apidocs.covidactnow.org/#register) using the API key and save a CSV file to local drive.


## Data Dictionary

| Variable                         | Description                                                  |Data types|
| -------------------------------- | -----------------------------------------------------------  |----------|
| actuals.cases                    | Cumulative confirmed or suspected cases. | int64 |
| actuals.deaths                   | Cumulative deaths that are suspected or confirmed to have been caused by COVID-19. | int64 |
| actuals.positiveTests.           | Cumulative positive test results to date| float64 |
| actuals.negativeTests            | Cumulative negative test results to date| float64 |
|actuals.contactTracers            | The number of people with whom a newly confirmed COVID patient has come into contact with. | float64 |
|actuals.newCases.                 | New confirmed or suspected cases| float64 |
|metrics.testPositivityRatio.      | Ratio of people who test positive calculated using a 7-day rolling average.| float64 |
|metrics.caseDensity               | The number of cases per 100k population calculated using a 7-day rolling average.| float64 |
|metrics.contactTracerCapacityRatio| | float64 |
|metrics.infectionRate             | R_t, or the estimated number of infections arising from a typical case| float64 |
|metrics.infectionRateCI90         | 90th percentile confidence interval upper endpoint of the infection rate.| float64 |
|riskLevels.overall                | Risk levels of catching Covid with level 5 for locations experiencing a severe outbreak | int64 |
|actuals.newDeaths                 | Number of deaths that are suspected or confirmed to have been caused by COVID-19 that day.| float64 |
|riskLevels.caseDensity            | Risk levels of catching Covid with level 5 for locations experiencing a severe outbreak | int64 |
|cdcTransmissionLevel              | The calculated level or category using the CDC's thresholds | int64 |
|metrics.weeklyNewCasesPer100k.    | | float64 |

                

 
## Initial Questions


##  Steps to Reproduce

