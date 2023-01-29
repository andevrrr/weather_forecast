# Weather forecast

![alt text](https://github.com/andevrrr/weather_forecast/blob/main/imagies/main_page.png?raw=true)

## Project Description

The goal was to create a webpage that will be able to handling weather data obtained via an API.
The weather data: 
- temperature
- wind speed 
- wind direction
- percentage of precipitation
- light level
- humidity level

comes from the weather station which is located on the roof of Tampere University of Applied Sciences in Tampere, Finland.

## Photos

![alt text](https://github.com/andevrrr/weather_forecast/blob/main/imagies/weather.png?raw=true)
![alt text](https://github.com/andevrrr/weather_forecast/blob/main/imagies/data.png?raw=true)
![alt text](https://github.com/andevrrr/weather_forecast/blob/main/imagies/data_intervals.png?raw=true)
![alt text](https://github.com/andevrrr/weather_forecast/blob/main/imagies/data_graph.png?raw=true)

## Backend API

- http://webapi19sa-1.course.tamk.cloud/v1/weather/temperature
- http://webapi19sa-1.course.tamk.cloud/v1/weather/rain
- http://webapi19sa-1.course.tamk.cloud/v1/weather/light
- http://webapi19sa-1.course.tamk.cloud/v1/weather/humidity_out
- http://webapi19sa-1.course.tamk.cloud/v1/weather/humidity_in

## Features

- 30 measurements fetched from the backend API. When index.html is opened with a browser, information is presented within an HTML page in tabular format. There are data rows corresponding to those 30 – and only 30 – measurements, and columns for these pieces of information:
◦ row number (1–30),
◦ measurement time,
◦ measurement type, and ◦ measured value.
The information presented in the table (in accordance with the data got via the API).

- a drop-down menu letting the user select a time interval to consider. The menu options are
• Now, the latest 20 measurements values are actual measured values,
• 24 hours, latest 24 hours, values are hourly averages,
• 48 hours, latest 48 hours, values are hourly averages,
• 72 hours, latest 72 hours, values are hourly averages, and
• 1 week, latest week, values are hourly averages.

- The data concerning the selected measurement type for the selected time interval is obtained using the API, presented in a table, and visualized using a line chart.

## Tech

- HTML/CSS
- JavaScript
