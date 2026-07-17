# Data-Pipelines-and-Automation
Project: Weather Data ETL Pipeline
​Project Overview
​This project demonstrates a basic ETL (Extract, Transform, Load) pipeline designed to collect live weather data from the OpenWeather API, transform it into a structured format using Python, and store it for further analysis.
​Data Source
​API: OpenWeather API
​Data Fields: City Name, Temperature, Humidity, Weather Condition, Wind Speed, and Date/Time.
​ETL Process
​Extract: Used the Python requests library to fetch current weather data for specific cities from the OpenWeather API.
​Transform: Utilized the pandas library to structure the raw JSON data, convert Unix timestamps into human-readable date/time formats, and ensure clean data types.
​Load: Saved the processed data into a structured CSV file (weather_data.csv) for future use.
​Tools Used
​Language: Python
​Libraries: Pandas, Requests
​Environment: Jupyter Notebook / VS Code
​API: OpenWeather API
​Steps Taken
​Generated an API key from OpenWeather.
​Wrote a script to loop through a list of cities and retrieve their weather metrics.
​Cleaned and reformatted the data using Pandas.
​Stored the final dataset as a CSV file.
​Key Findings
​Performed basic analysis on the extracted data, such as comparing temperatures across cities and identifying the city with the highest humidity level.
​The pipeline successfully automated the process of moving from raw API input to a clean, analysis-ready dataset.
### project demo
watch the project walkthrough here https://drive.google.com/file/d/17C2AvfC2p8gqWatNwKT6cQYJGJQPLo6C/view?usp=drive_link
