# Web_scraping_challenge

Web Scraping Challenge

Overview

This project involves scraping and analyzing data from Mars-related sources and is divided into two main parts: scraping news data and analyzing weather data. The objective is to automate data extraction and perform various analyses to gain insights into Mars' weather and news.

Requirements

Part 1: Scrape Titles and Preview Text from Mars News
For the first part of the project, automated browsing was conducted using Splinter to visit the Mars news site. The HTML code was then extracted using Beautiful Soup. The titles and preview text of news articles were scraped and successfully extracted. This information was stored in a Python list of dictionaries, with each dictionary representing a news article.

Part 2: Scrape and Analyze Mars Weather Data
The second part of the project involves scraping and analyzing Mars weather data. The HTML table containing weather data was extracted into a Pandas DataFrame. Data was scraped using either Pandas read_html or a combination of Splinter and Beautiful Soup. The DataFrame includes the correct column headings and data types.

Data analysis was performed to answer specific questions. First, the number of Martian months was determined. Next, the total number of Martian days' worth of data available was calculated.

Additionally, various data visualizations and analyses were conducted. This includes identifying which Martian month, on average, has the lowest and highest temperatures and atmospheric pressures. The number of terrestrial days in a Martian year was estimated visually within a 25% margin.

Finally, the DataFrame was exported into a CSV file for further analysis.

Sources

Special thanks to the following individuals and resources for their contributions and support:

Professor Melissa Ingle – Lead Instructor, providing valuable guidance and feedback throughout the project.
Chris Rahal – Classmate, contributing to discussions and collaborative problem-solving.
Cassidy Cruz – Classmate, assisting with data analysis and brainstorming.
ChatGPT – AI assistant for answering questions, providing code suggestions, and clarifying concepts.
Xpert Learning Assistant – Additional learning resource for supplementary support during the project.