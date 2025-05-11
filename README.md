# Bikesharing

Rental bikes are increasingly being introduced in urban cities to enhance mobility and provide greater convenience. Ensuring these bikes are available and accessible to the public at the right time is essential, as it reduces waiting times and improves user satisfaction. Maintaining a stable supply of rental bikes across the city is a significant challenge, with the most critical aspect being the accurate prediction of bike demand at different hours. My goal is to develop a highly accurate model with minimal error that not only forecasts bike demand but also provides insights into the key factors influencing usage. These insights will enable bike-sharing companies to make data-driven decisions and optimize their operations effectively.


# Objective:Predication of bike rental count hourly based on the environmental and seasonal settings.

# Source: https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset

# Features:

instant: Record index
dteday: Date
season: Season (1: spring, 2: summer, 3: fall, 4: winter)
yr: Year (0: 2011, 1: 2012)
mnth: Month (1 to 12)
hr: Hour (0 to 23)
holiday: Whether the day is a holiday (1: holiday, 0: non-holiday)
weekday: Day of the week (0: Sunday to 6: Saturday)
workingday: If the day is neither a weekend nor a holiday (1: working day, 0: otherwise)
weathersit: Weather condition (1: Clear, 2: Mist, 3: Light snow/rain, 4: Heavy rain/ice)
temp: Normalized temperature in Celsius
atemp: Normalized feeling temperature in Celsius
hum: Normalized humidity
windspeed: Normalized wind speed
casual: Number of casual users
registered: Number of registered users
cnt: Total count of bike rentals (target variable)
