# TOURISTA

A web application that allows users to create travel itineraries for their vacations.


## API Keys
- Visual Crossing Weather API Key: [Sign up](https://www.visualcrossing.com/weather-api) for a free account and get your API key.
- Google Palm API: [Sign up](https://makersuite.google.com) for a free account and get your API key.


## To run application:
1. Open up terminal and change directory (cd) until your current working directory is the directory containing "run.py".
2. Type `pip install -r requirement.txt`.
3. Populate .env according to .example.env file.
4. Type `python run.py` and hit enter.
5. Open up any web browser on the same machine and go to the address `localhost:5001`.

### Note:
To use the database functionality, before you run the application for the first time, you will need to do the following.

1. Type `mysql -u root -p < team1-schema.sql` into your terminal and hit enter.
2. Enter your mysql password.
3. Type `mysql -u root -p < team1-data.sql` into your terminal and hit enter.
4. Enter your mysql password.
