# The Battle of the Neighborhoods

## Introduction

<font size="3"> With Covid-19 becoming the one of the most dominant pandemics in recent history, many aspects of a "common lifestyle" have disappeared. Tourism, once a strong contributor to a city's economic standing, has become almost non-existant around parts of the world. With the majority of the population restricted from outdoor activities, many tourist destinations and businesses have faced uncountable hardships and challenges in an effort to stay relevant and in business. <font>
    
<font size="3"> For many cities and countries, tourism is the primary source of income. It boosts the economy and supports many local small business. With vaccines becoming more widely available and the public becoming more comfortable with travel, it would be wise to consider opening a restaurant or a small business in popular tourist destinations. <font>


    

## Business Problem

<font size="3"> Chicago has faced numerous difficulties over the past year. Many small businesses have shut down and tourism, which usually plays a crucial role in Chicago's economic standing, is at an all time low. The objective of this project is to analyze and determine the optimal locations and neighborhoods to open a restaurant or a small business in the city of Chicago. These locations should be determined such that it will favor the business and contribute to overall the tourism of the city.   <font>

## Data

<font size="3"> To best approach the problem mentioned above, we will require data that contains the following information:  </font>
    
    - All neighborhoods of the city of Chicago
    - All businesses and business types in the city of Chicago
    
    
<font size = "3"> Source: We will extract all the necessary information and data from a Wikipedia page (https://en.wikipedia.org/wiki/List_of_neighborhoods_in_Chicago) containing all neighborhoods in Chicago. The beautifulsoup4 library in Python will help to webscrape all the neighborhood information from the Wikipedia page. We will also be using the Foursquare API to get all relevent information pertaining to businesses present in Chicago.</font>
    


```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
import requests
import csv
import json
from pandas.io.json import json_normalize
from geopy.geocoders import Nominatim
import requests
import matplotlib.cm as cm
import matplotlib.colors as colors
from matplotlib.colors import rgb2hex
from sklearn.cluster import KMeans
import math
from bs4 import BeautifulSoup
```


```

```
