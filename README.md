# Mars Web Scraping and Data Analysis Project

## Project Description

This project aims to extract and analyze data from Mars-related websites to gain insights into Mars news and its weather conditions. The objective is to provide a clear understanding of recent Mars exploration news and detailed analysis of temperature and atmospheric pressure data collected by the Curiosity rover.

By uncovering trends in Mars weather and summarizing current Mars news, this project benefits researchers, space enthusiasts, and educators by making Mars exploration data accessible and understandable.

## Dataset Description

Two main datasets were used:

* Mars news articles scraped from NASA's Mars News website via an educational platform created by the University of Toronto.
* Mars weather data sourced from the Curiosity rover's observations, available on a dedicated Mars temperature data site maintained for educational use.

Both datasets were collected through web scraping techniques.

## Methodology

The project consists of two parts:

**Part 1: Mars News Scraping**

* Automated browsing was done with Splinter to navigate the Mars News site.
* Beautiful Soup extracted titles and preview text of news articles.
* The data was organized into Python dictionaries and stored in a list for further use.

**Part 2: Mars Weather Data Scraping and Analysis**

* The Mars temperature data site was visited using automated browsing.
* Beautiful Soup scraped the relevant HTML table containing weather data.
* Data was assembled into a Pandas DataFrame with columns like 'id,' 'terrestrial\_date,' 'sol,' 'month,' 'min\_temp,' and 'pressure.'
* Data types were checked and converted as needed for analysis.
* Key questions about Mars weather were answered using Pandas functions and visualized with bar charts and plots.
* The final processed dataset was saved as a CSV file for future reference.

## Key Findings

**What are the characteristics of Mars weather data?**

* Mars has 12 months.
* Approximately 1867 Martian days (sols) of weather data were analyzed.

**Which month is the coldest and warmest on Mars?**

* The third month recorded the coldest average minimum temperature.
* The eighth month had the warmest average temperature.

**How does atmospheric pressure vary throughout the Martian year?**

* The lowest atmospheric pressure was in the sixth month.
* The highest pressure occurred in the ninth month.

**What is the estimated length of a Martian year?**

* Daily minimum temperature trends suggest a Martian year lasts about 675 Earth days, consistent with known scientific data.

**What insights were gained from Mars news scraping?**

* Recent news articles were successfully scraped, providing up-to-date information on Mars exploration events and discoveries.

## Conclusion

The project effectively demonstrates the use of web scraping and data analysis to collect and interpret Mars-related information. It combines automated web browsing, HTML parsing, and data manipulation techniques to provide meaningful insights into Mars weather patterns and recent news. The approach contributes to making complex space data more accessible and understandable.

## Recommendations

Future efforts could focus on expanding the scope of data sources to include other Mars missions or datasets, enhancing visualization methods to better illustrate trends, and applying machine learning techniques to predict future Mars weather conditions based on historical data.

## Credits

This project was developed as part of the University of Toronto Boot Camp certification program. The Mars News website and Mars weather data sites were created by the University of Toronto for educational purposes.

News content was scraped from NASA's Mars News website, with images used following NASA/JPL-Caltech image use policies.
