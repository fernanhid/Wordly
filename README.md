# Worldly: The News Topic App

Worldly's goal is to allow anyone to get an understanding of how different parts of the world respond to international events. I scraped data from 5 different nnewspapers and used NMF Topic Modeling to extract topics from over 3 years worth of data. Worldly is a D3.js tool however, there are seaborn graphs that also display article volume through time in notebook <a href = 'https://github.com/fernanhid/Wordly/blob/master/3.comparing_countries.ipynb'>number 3</a>. Feel free to use any code that you think is useful!  <br>/
The newspapers include:<br>

a. New York Times (U.S.)<br>
b. La Republica (Peru)<br>
c. The Guardian (U.K.)<br>
d. Times of India (India)<br>
e. China Today (China)<br>
f. The Age (Australia)<br>

This is how the notebooks are organized:

1. Data Acquisition (scrapping & API's), Cleaning, Storing (MongoDB, Pickle)
2. (a-f) Topic Modeling(NMF)/ Exploration
3. Country by country visualizations of topics over time

Some of the Interesting Insights I found:

1. India focused on Brexit before anyone else
2. Peru and the U.S. focused on the arrival of Pope Francis
3. The U.K. covered Zika the most even though it's in the least danger
