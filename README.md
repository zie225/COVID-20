# COVID-19

Update on 3 May 2020: I attempted ARIMA and FB Prophet models to forecast future infections. Both models behaved badly!

Exploratory Data Analysis using open source datasets such as NYT
I'm using an open-source dataset available from the New York Time: 'https://github.com/nytimes/covid-19-data/raw/master/us-states.csv' / https://github.com/nytimes/covid-19-data

The aim is to generate simple charts to visualize and help us understand the trend of infection growth / decrease and most improtantly seeing if states are flattening the curve.

I'll try to update and comment the code regularely, nonetheless, it should be clear to the reader. Happy to answer any questions.

Next ambitions in future updates:
- Similar charts to other US States: Virginia added already
- Include Canada
- Properly functioning Choropleth maps (I'm still having trouble with the scale because of NEw York and New Jersey numbers being outliers compared to other states)
- I'll attempt county level analysis for a few states as well
