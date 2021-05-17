## Analyzing Maryland Crashes from 2015 to 2020 by Pranav Pappala
```{python}
  print("Hello!")
```
The start of this data analysis starts with a personal observation.

Maryland is notorious for bad drivers and bad driving. Personal story, my parents' car insurance used to be 300 dollars with me, and that was a really good deal due to their safe driving habits and good credit. The moment we moved to Maryland, that number close to tripled and reached roughly 1000 dollars. I learned that the main reason why that figure shot up was because Maryland drivers got into a lot of crashes, so to compensate, the premiums from the insurance companies went up quite a bit.

So, I was motivated to understand what factors can predict a crash with Maryland vehicles, so I looked at the official Maryland open data websites funded by the state government.

Here are the libraries that were used as well as references to them for future data science use.

Numpy -> used for certain mathematical functions that make predictions easier

Pandas -> used to place data from files and place them in dataframes

Matplotlib -> used to help plot data in a 2D figure for simple analysis

Scikit-learn -> used to help create predictive model for crash severity

Seaborn -> used to help plot and highlight correlations in data

Folium -> used to help map Maryland as well as the crashes that occurred

The first dataset is a CSV file of Maryland statewide vehicle crashes garnered from official crash reports from 2015-2020 which was retrieved from this website: https://opendata.maryland.gov/Public-Safety/Maryland-Statewide-Vehicle-Crashes/65du-s3qu

The second dataset is a CSV file of vehicle details garnered from the exact same set of official crash reports from 2015-2020 which was retrieved from this website: https://opendata.maryland.gov/Public-Safety/Maryland-Statewide-Vehicle-Crashes-Vehicle-Details/mhft-5t5y

With that personal story in mind, I wanted to focus on some of the aspects behind the severity of a crash in Maryland. Do some crashes happen more in certain areas of Maryland than others? Do some features (like road conditions or daylight conditions) suggest a crash is more likely to happen?

I would also like to determine correlations between damage and movement descriptions to see if there is a certain type of movement that causes worse crashes than others. I want to create a correlation matrix for the vehicle type in the crash to find out if correlations exist between items such as the model and severity using seaborn, or vehicle year and damage.

To end this all, could one predict the damage done to a vehicle in a crash using only a select few features with decent correlation?

`{python} import numpy as np\n
import pandas as pd\n
import matplotlib.pyplot as plt\n
import sklearn\n
import seaborn as sns\n
import folium
import random`

[Link](url) and ![Image](src)
