
# DATA COLLECTION-CHALLENGE

## Description
### This challenge focuses on applying web-scraping and data analysis skills to gather, process, and interpret data from online sources. The objective is to enhance capabilities in data collection, organization, and visualization to derive meaningful insights.

### The project is divided into two parts, each producing a distinct deliverable:
1.	__Mars News Scraper__: Scrape titles and preview text of news articles from the Mars News website. __Script (part_1_mars_news.ipynb)__
2.	__Mars Weather Data Analysis__: Scrape and analyze Mars weather data from an HTML table. __Script (part_2_mars_weather.ipynb)__

## Key Insights
-   Number of months on Mars: 12
-   Total Martian days of data available: 1867
-   Temperature Trends: Mars experiences significant temperature variations, with the coldest month being Month 3 (-83.31°C) and a     warming trend peaking at Month 8 (-68.38°C).  
-   Atmospheric Pressure Trends: Atmospheric pressure fluctuates, reaching a minimum in Month 6 (745.05 Pa) and a peak in Month 9 (913.31 Pa).  
-   Martian Year Length: Temperature cycles suggest that a Martian year spans approximately 687 Earth days, aligning with known scientific data.  

## Outputs
-   Organized list of Mars news titles and previews (mars_news.json)
-   A structured Mars weather data file (mars_data.csv)
-   bar chart for temperature (avg_temp_by_month.png), for atmospheric pressure (avg_pressure_by_month.png), Visualization of Martian year length (mars_data_df.png)

### temperature
![temperature](avg_temp_by_month.png)

### atmospheric pressure
![atmospheric pressure](avg_pressure_by_month.png)

### Visualization of Martian year length
![Martian year length](mars_data_df.png)
 
## Tools and Libraries 
-   Web scraping: Splinter, Beautiful Soup 
-   Data handling: Pandas
-   Visualization: Matplotlib

__Note__: Install selenium and import webdriver if there is an error in running the Browser 

## Installation
git clone: https://github.com/geraldine1456/data_collection-challenge.git

## References
-   The Mars News website is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars News website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.  
-   Microsoft Co-pilot for debugging assistance

