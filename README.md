# Behind the Sold Sign: A Data-Driven Exploration of Kungälv's Real Estate Market

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)




## Project Overview

This project focuses on extracting and analyzing real estate sales data from Hemnet, Sweden’s most popular property listing website. The dataset consists of HTML files scraped from Hemnet in October 2023, specifically covering house sales in Kungälv. Using Python and Beautiful Soup, I parsed the HTML files to extract relevant details such as the sale date, address, location, living area, number of rooms, plot size, and final sale price. The extracted data was cleaned and compiled into a structured CSV file for further analysis.

The analysis centers on the houses sold during 2022. I performed statistical summaries including the five-number summary (minimum, first quartile, median, third quartile, and maximum) of the closing prices. To better understand the distribution of sale prices, I created a histogram applying the square root rule to determine the optimal number of bins. Additionally, scatter plots were constructed to explore the relationship between closing price and living area, with one version color-coded based on the number of rooms to highlight patterns between size, price, and house configuration.

From the visualizations and summaries, some interesting trends emerged: larger houses with more rooms tend to be priced higher, while smaller houses are clustered at lower price points. Most houses sold fall within a price range of 2 to 6 million SEK and a size between 50 and 200 square meters. There are a few outliers—very large and expensive properties that stand out in the data. These insights provide a clear picture of the housing market dynamics in Kungälv for 2022.



