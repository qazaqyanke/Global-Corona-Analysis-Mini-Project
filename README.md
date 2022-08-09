# Global Corona Analysis Mini Project
I In the history of mankind, there have been several pandemic situations.

I Every time a new epidemic appears, mankind has been trying to find new vaccines and treatments. In each case, the
most important role was to conduct reliable epidemiological investigations and transparently disclose the results.

I Mankind created new vaccines and treatments based on publicly released data and tried to find a way until an
alternative is available.

I In the pandemic situation, various data analysis, such as how many people are currently infected? where are the
regions where infected people are currently decreasing? what is the age and living environment where the number of
infected people is high? and whether the number of infected people is decreasing due to the effectiveness of the
vaccine? and data visualization for people to understand easier have made a lot of contributions.

I Through this mini-project, we are also trying to get descriptive statistics on which countries have the highest number
of infections based on the corona-related data available to the public.

I The result will display the cumulative infection level on a map of the world so that anyone can check it at a glance.

I We use the data from the [Coronavirus (COVID-19) Vaccinations] database collected in real time by
https://ourworldindata.org/

I We can use the data required for practice in "./data//covid/covid-vaccination-doses-per-capita.csv".

I For reference, we need to understand that there are some data are excluded because some countries do not disclose
the data to the world, but we can still practice with the data provided.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages

```bash
pip install numpy
```
```bash
pip install pandas
```
```bash
pip install matplotlib
```
```bash
pip install folium
```

## Usage Example

```python
import numpy as np
import pandas as pd
import datetime
import matplotlib.pyplot as plt
from datetime import date, datetime, time, timezone

df = pd.read_csv("./covid-vaccination-doses-per-capita.csv")
df.info()

```

```python
import folium
map = folium.Map(location=[latitude, longitude, zoom_start=12)
map
```

## License
[MIT](https://choosealicense.com/licenses/mit/)