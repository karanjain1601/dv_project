# Install Dependencies from terminal:
```bash
pip install dash
pip install dash-bootstrap-components
pip install folium
pip install plotly
pip install pandas
pip install requests
```

## Using OpenWeatherMap Geolocation API to get the location of the city


"http://api.openweathermap.org/geo/1.0/direct?q={city}&limit=1&appid={api_key}"


Replcae {city} with the name of the city and {api_key} with your API key

In cell three of the notebook, replace the your_api_key with your own api key
```python
api_key = "your_api_key"

```

# Run the app from terminal:
Open the terminal in dv_project directory
```bash
ipython -c "%c main.ipynb"
```
or directly from jupyter notebook using Run All button in main.ipynb


You can create your API key from https://openweathermap.org/api

# Github Link
https://github.com/karanjain1601/dv_project

