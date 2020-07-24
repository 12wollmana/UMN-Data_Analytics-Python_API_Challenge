# What's the Weather Like?

## WeatherPy
This folder contains code to call up OpenWeatherMaps' API to find trends in weather data for random cities.
After running the code, a [CSV](WeatherPy/output_data/cities.csv) will be saved with the weather data.

## VacationPy
This folder contains code to try to find a good vacation spot using the data generated in WeatherPy.
The code calls into Google's places and figure APIs to find hotels and display a heatmap of the humidity.

## How to Run
<ol>
  <li>
    In the root folder, create a file called api_keys.py. In this file, define two variables:
    <ul>
      <li><i>weather_api_key</i> will be a key from OpenWeatherMaps.</li>
      <li><i>g_key</i> will be a key from Google Developers.</li>
    </ul>
  </li>
  <li>In the terminal, initialize an Anaconda environment using "source activate <i>{your environment}</i>".</li>
  <li>Open Jupyter Notebook using "jupyter notebook" in the terminal.</li>
  <li>In the Jupyter Notebook, open the ipynb file that contains the code.</li>
  <li>
    With the code open, you have two options on how to run the code:
    <ul>
      <li>
        In the menu bar open Kernel > Restart and Clear Output.  Then you can use Shift+Enter to run the code one block at a time.
      </li>
      <li>In the menu bar open Kernel > Restart and Run All.  This will run all of the blocks of code at once.</li>
    </ul>
  </li>
</ol>
