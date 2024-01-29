# Mars Web Scraping and Data Analysis Project
## Background
This project involves web scraping data from two Mars-related websites and performing data analysis on the extracted information. The goal is to gain insights into Mars news articles and analyze temperature and atmospheric pressure data from the Curiosity rover.

## Project Structure
The main repository branch includes the following folders:

mar_temperature_data: Contains the CSV file with the analyzed Mars weather data.
part_1_mars_news: Jupyter Notebook for scraping titles and preview text from Mars news articles.
part_2_mars_weather: Jupyter Notebook for scraping and analyzing Mars weather data.

## Project Overview
This project consists of two main deliverables:

## Deliverable 1: Scrape Titles and Preview Text from Mars News
### Step 1: Visit the Mars News Website
Automated browsing with Splinter was used to visit the Mars news site at Mars News Site. The webpage was inspected to identify the HTML elements to scrape.

### Step 2: Scrape the Website
Beautiful Soup was utilized to create a BeautifulSoup object and extract text elements from the Mars News website. Titles and preview text of news articles were scraped and stored in Python data structures.

### Step 3: Store the Results
The scraped information was stored in Python dictionaries, where each dictionary represents a news article with keys for 'title' and 'preview'. All dictionaries were then stored in a Python list. The list was printed in the Jupyter Notebook for verification.

## Deliverable 2: Scrape and Analyze Mars Weather Data
### Step 1: Visit the Mars Temperature Data Site
Automated browsing was employed to visit the Mars Temperature Data Site at Mars Temperature Data Site. The webpage was inspected to identify the HTML elements to scrape.

### Step 2: Scrape the Table
Beautiful Soup was used to create a BeautifulSoup object and extract data from the HTML table. The extracted data was then assembled into a Pandas DataFrame with appropriate column headings.

### Step 3: Store the Data
The scraped data was stored in a Pandas DataFrame with columns such as 'id,' 'terrestrial_date,' 'sol,' 'ls,' 'month,' 'min_temp,' and 'pressure.' The DataFrame was displayed to verify its successful creation.

### Step 4: Prepare Data for Analysis
Data types of each column were examined, and necessary type conversions were performed. The DataFrame was modified to ensure proper data types for analysis.

### Step 5: Analyze the Data
Pandas functions were used to analyze the dataset and answer specific questions about Mars weather:

The number of months on Mars.
The number of Martian days' worth of data.
The coldest and warmest months on Mars, visualized with a bar chart.
The months with the lowest and highest atmospheric pressure on Mars, visualized with a bar chart.
An estimate of the number of terrestrial days in a Martian year, visualized by plotting the daily minimum temperature.

### Step 6: Save the Data
The final DataFrame was exported to a CSV file for future reference.

## Project Results and Findings

### Deliverable 1: Mars News Articles
The scraping of Mars news articles was successful, resulting in a list of dictionaries containing titles and preview text. Each dictionary represents a news article, providing valuable insights into recent Mars-related events and discoveries.

### Deliverable 2: Mars Weather Data Analysis
The analysis of Mars weather data revealed interesting patterns:

#### Findings:
The analysis revealed 12 months on Mars, with approximately 1867 Martian days' worth of data.

The third month exhibited the coldest average minimum temperature, while the eighth month was the warmest.

Atmospheric pressure was lowest in the sixth month and highest in the ninth.

A cyclical pattern in daily minimum temperatures suggested a Mars year of around 675 Earth days, confirmed by an internet search.

## Conclusion
This project showcases the application of web scraping techniques to gather Mars-related information and the utilization of data analysis to derive meaningful insights. The combination of Splinter, Beautiful Soup, and Pandas facilitated the extraction, manipulation, and analysis of data, contributing to a comprehensive understanding of Mars weather and recent news.

## Note:
This project was developed as part of the University of Toronto Boot Camp certification program. The websites used for scraping were created by the University of Toronto for educational purposes.

## Reference:
The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.
