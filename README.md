# API-Challenge

I used **Python, Pandas, NumPy, DateTime, Matplotlib and [OpenWeatherMap API](https://openweathermap.org/api)** to visually analyze the weather of 500 random cities globally.

1. I created lists of 500 random lat and long coordinates and found the nearest cities using [CitiPy](https://github.com/wingchen/citipy).
2. I queried [OpenWeatherMap API](https://openweathermap.org/api) to retrieve the JSON data for each city, and complete a dataframe. The results were also saved to a CSV.
3. I designed scatter plots to show various weather relationships to latitude:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

4. Based on the scatter plots, I wrote a summary description of any observed relationships and possible further studies.
