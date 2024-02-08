## I have included web scraping projects involving tabular data using Python in this repository.

### About Web Scraping from Tabular Data:
Web scraping from tabular data refers to the process of extracting structured, organized information presented in tabular format from web pages. Tabular data is often arranged in rows and columns, resembling a table. Web scraping from table data typically includes steps like selecting the relevant rows and columns, and extracting the information for further analysis or storage. This can be done using programming languages like python and libraries such as BeautifulSoup and Selenium. 

### Project1 Description. 
- Project Name: **SCRAPING TABULAR DATA FROM BOX OFFICE MOJO WEBSITE FOR TOP MOVIES GROSS MARGIN.**
- The goal is to gather information about the gross margins of the top 200 movies, including details like rank, name, total gross, and release date.
- In the project, I have used python libraries BeautifulSoup, requests, and pandas for efficient web scraping.
- Initially using requests library I get a 200 response, ensure successful communication with the Box Office Mojo server.
- Then, using BeautifulSoup libaray, extract the response content and store it in the info variable.
- Utilize the find and find_all functions of BeautifulSoup to navigate the HTML structure and extract the tabular data.
- Use a python for loop to systematically go through the website's content.
- Initially, I extract the column names and create a dataframe using them. In the next step, I extract all the data and append it to the dataframe.
- Gathered detailed information for the top 200 movies to ensure a comprehensive dataset.
- Transform the dataframe into a CSV file for enhanced usability.
-  The structured dataset is ready for immediate use in data analysis, visualization, unlock valuable insights about movies effortlessly.

### Project2 Description. 
- Project Name: **SCRAPING ASIAN GAMES 2023 MEDAL TABLE DATA FROM JAGRANJOSH WEBSITE.**
- The scraped data is organized into columns representing the rank, country, gold, silver, bronze, and total medals achieved at the Asian Games 2023.
- In this project, I followed a similar methodology as in Project 1, implementing python web scraping tools like BeautifulSoup and Requests.
- The data extraction process involved obtaining medal table information from the JagranJosh website, structuring it into columns such as Rank, Country, Gold, Silver, Bronze, and Total.
- The final step included exporting this organized dataset into a CSV file.
- Explore medal standings, identify trends, and derive insights into the performance of countries at the Asian Games 2023.

### Project3 Description. 
- Project Name: **SCRAPING TABLE DATA OF TOP 100 NSE MIDCAP COMPANIES FROM MONEYCONTROL WEBSITE.**
- The aim is to extract detailed stock market information for the top 100 NSE Midcap companies from Moneycontrol.
- In this project, I have used selenium library, selenium functions such as webdriver, Service, By.
- Utilize the Selenium library to automate web interactions and extract dynamic table data from the Moneycontrol website.
- Initially extract the column names using find_elements function, By.XPATH. And created dataframe. 
- Stock market data columns, including company name, last traded price, percentage change, volume, buy price, sell price, buy quantity, and sell quantity.
- Then using same function find_elements, I extract the data about each companie, and append to the dataframe.
- Created structured dataframe and then transform into CSV file to use further.
- Gain access to crucial stock market data of top NSE Midcap companies for analysis, visualization, and informed investment decisions.

### Project4 Description. 
- Project Name: **SCRAPING TABULAR DATA OF CWC2023 QUALIFIER FROM MONEYCONTROL CRICKETWORLD WEBSITE.**
- Aims to create a comprehensive dataset for cricket analysts, and fans interested in tracking the progress batsmen's in the CWC2023 Qualifier.
- For this project, I used similar methodology of Project 1/2, utilizing Python web scraping tools such as BeautifulSoup for parsing and Requests for fetching data.
- The dataset includes player statistics with columns representing Matches, Innings, Not Outs, Runs Scored, Highest Score, Batting Average, Balls Faced, Strike Rate, Centuries, Half-Centuries, Sixes and Fours.
- Then Transform dataset to CSV file.
- This dataset offers a detailed look at CWC2023 Qualifier, specifically focusing on batsmen's statistics.

### Project5 Description. 
- Project Name: **SCRAPING TABLE DATA OF TOKYO OLYMPICS MEDAL TABLE FROM BBC SPORT WEBSITE.**
- The aim of this project is to automate the extraction of Tokyo Olympics medal table data, including columns for Rank, Country, Gold, Silver, Bronze, and Total, from the BBC Sport website.
- Utilized Python libraries: BeautifulSoup, requests, and pandas for efficient web scraping.
- Started by obtaining a 200 response using the requests library, Employed BeautifulSoup to parse data from the BBC Sport website.
- Created a table variable to store table-related content from the webpage, Utilized find and find_all functions in Python and core python coding to extract the necessary data.
- Constructed a DataFrame using pandas to organize the extracted dataset, then converted the dataset into a CSV file.
- This project offers a streamlined solution for retrieving correct Tokyo Olympics medal table data, empowering analysts with readily accessible and structured information for in-depth insights and visualization.
