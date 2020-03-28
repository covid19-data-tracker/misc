# Miscellaneous 

## Goals 
* Ingest and accumulate the data about COVID, with a focus initially on my own country, the United States of America 
* The idea is to monitor Github repositories [with webhooks](https://developer.github.com/webhooks/) to trigger a Lambda function which will then launch this Spring Batch job and update a statically-generated site containing the data.

## Data 
This repository contains random artifacts that I'll use in this site. 

* The New York Times has kindly put out information people can use to monitor the flow of the outbreak in the US, [available here](https://github.com/nytimes/covid-19-data). That data is on Github and it powers there already [superb visualization of the data here](https://www.nytimes.com/interactive/2020/us/coronavirus-us-cases.html#g-cases-over-time)
* There are a ton of useful [projects out there to support processing](https://github.com/soroushchehresa/awesome-coronavirus)
* Here's [some data with breakdowns from India](https://github.com/covid-19-tracker/india-state-wise)
* Here's some data [tracking worldwide infections](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_19-covid-Confirmed.csv)
