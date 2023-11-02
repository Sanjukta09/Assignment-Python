** Project Report: Investigating Nintendo Games Using Python, Web Scraping **

Introduction
In this project, I aimed to analyze the sales data of Nintendo games using Python. To enhance our dataset, I performed web scraping to gather additional information from a gaming database. Then analyzed the combined dataset and created an interactive dashboard using Streamlit for an informative presentation.

Data Source
The primary dataset for this project was obtained from Kaggle, which is a comprehensive collection of Nintendo games data. The dataset provides details such as game titles, release dates, platforms, and sales figures.

Dataset Source: Nintendo Games Dataset on Kaggle

To supplement the primary dataset, I utilized web scraping techniques to fetch additional information from VGChartz, a popular gaming database.

Web Scraping Source: VGChartz Game Database

Methodology
Data Gathering:

I started by downloading the primary Nintendo games dataset from Kaggle.
For web scraping, I used Python libraries such as BeautifulSoup and Requests to extract information from VGChartz. The data extracted includes user and critic ratings, developer information, and additional sales data.
Data Cleaning and Preparation:

I cleaned the primary dataset by handling missing values, data type conversions, and duplicate records.
The scraped data required cleaning and merging with the primary dataset. This involved matching games by title, platform, and release date.
Data Analysis:

After combining the datasets, I conducted exploratory data analysis (EDA) to gain insights into the sales and ratings of Nintendo games. I performed descriptive statistics and visualizations to understand the data better.


Conclusion
In this project, I successfully investigated Nintendo game sales by merging a Kaggle dataset with additional data obtained through web scraping. I then performed data analysis to uncover interesting trends and patterns within the Nintendo gaming industry. 

This project demonstrates the power of Python, web scraping in data analysis and presentation, and it can be extended to further explore the gaming industry or other domains.
