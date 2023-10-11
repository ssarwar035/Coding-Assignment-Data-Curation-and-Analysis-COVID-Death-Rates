# Coding-Assignment-Data-Curation-and-Analysis-COVID-Death-Rates
Data scraping using BeautifulSoup API from Wikipedia's COVID-19 pandemic death rates by country

DESCRIPTION
- The goal of this project is to scrape data from a site to create new data. The data is to be analyzed and visualized.

SUMMARY
- The project aimed to collect and analyze data on COVID-19 deaths by country from Wikipedia. COVID-19 has had a significant global impact, and understanding the variations in the number of deaths across countries is crucial for public health and policy decisions. This project sought to scrape data from Wikipedia, perform data cleaning, and visualize the results using scatter plots and bar graphs.

Methods:

- Data Collection: We used web scraping techniques to gather COVID-19 death data from Wikipedia. The primary data source was a Wikipedia table containing information on deaths per million, total deaths, and total cases for various countries.
    We used pandas and BeautifulSoup to scrape and organize the data in data frames and transform the data in a way that would be useable       and analyzable.
- Data Cleaning: The collected data required cleaning, as it often contained non-numeric characters, missing values, and unnecessary information. We transformed the data into a structured format, handling issues like missing values and non-numeric characters. Additionally, we excluded irrelevant data entries, such as "World", and "European Union", and took out the last row of data as it was not applicable.
- Data Analysis: We conducted various analyses on the cleaned dataset, including
    Scatter Plots: We created scatter plots to visualize the relationship between the number of COVID-19 cases and deaths in different           countries. This allowed us to identify patterns, outliers, and correlations.
    Bar Graphs: To provide an overview of COVID-19 death statistics by country, we used bar graphs to display the top countries with the         highest death rates, total deaths, and cases.

The project revealed several key findings, such as:

- Identifying countries with high COVID-19 death rates.
- Visualizing the relationship between cases and deaths, highlighting countries with varying trends.
- Providing a concise summary of COVID-19 death statistics for specific countries allows for easy comparison.

Discussion: It is worth noting that the data analysis also revealed disparities in COVID-19 death rates, particularly in third-world countries. These nations often faced higher death rates due to various factors, including limited healthcare infrastructure, lack of resources, and challenges in access to vaccines and medical care. The project's findings underscored the importance of global collaboration and assistance in supporting these countries during the pandemic.

Data types and attributes:

- "Country": The name of the country for which COVID-19 data is recorded. (String)
- "Total Deaths": The total number of deaths due to COVID-19 in the country. (Int)
- "Total Cases": The total number of confirmed COVID-19 cases in the country. (Int)
- "Deaths per Million": The number of COVID-19 deaths per million people in the country. (Int)

Wikipedia contributors. (2023, August 19). COVID-19 pandemic death rates by country. In Wikipedia, The Free Encyclopedia. Retrieved 04:20, October 11, 2023, from https://en.wikipedia.org/w/index.php?title=COVID-19_pandemic_death_rates_by_country&oldid=1171087885
