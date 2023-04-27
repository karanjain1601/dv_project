# Install Dependencies from terminal:
```bash
pip install dash
pip install dash-bootstrap-components
pip install folium
pip install plotly
pip install pandas
```

# Run the app from terminal:
```bash
ipython -c "%c main.ipynb"
```
or directly from jupyter notebook using Run All button

## Using OpenWeatherMap Geolocation API to get the location of the city


"http://api.openweathermap.org/geo/1.0/direct?q={city}&limit=1&appid={api_key}"


Replcae {city} with the name of the city and {api_key} with your API key

In cell three of the notebook, replace the api_key with your own api key
```python
api_key = "your_api_key"

```

