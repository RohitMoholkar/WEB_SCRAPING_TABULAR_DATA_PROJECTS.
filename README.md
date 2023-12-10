## I have included Web Scraping from Tabular Data Projects using Python in this Repository.

### About Web Scraping from Tabular Data:
Web scraping from tabular data refers to the process of extracting structured, organized information presented in tabular format from web pages. Tabular data is often arranged in rows and columns, resembling a table. Web scraping from table data typically includes steps like selecting the relevant rows and columns, and extracting the information for further analysis or storage. This can be done using programming languages like python and libraries such as BeautifulSoup and selenium. 

### About Python requests Library:  
The requests library used to send HTTP requests and handle the corresponding responses, makes it easier for data engineer/developers to interact with web services and retrieve data from URLs. 

### About Python BeautifulSoup Library: 
Beautiful Soup is a python library designed for pulling data out of HTML and XML files. It provides a convenient way to navigate, search, and modify the hierarchical structure of a source code, making it easier to scrape and extract information from web pages. 

### About Python selenium Library: 
The selenium library is used to extract data from dynamic web pages, it can execute javascript and dynamically load content, also to scrape data from infinite scroll web pages selenium is very useful.  

### Project1 Description. 
- Project Name: **SCRAPING TABULAR DATA FROM BOX OFFICE MOJO WEBSITE FOR TOP MOVIES GROSS MARGIN.**
- The goal is to gather information about the gross margins of the top 200 movies, including details like rank, name, total gross, and release date.
- In the project, I have used python libraries BeautifulSoup, requests, and pandas for efficient web scraping.
- Initially using requests library I get a 200 response, ensure successful communication with the Box Office Mojo server.
- Then, using BeautifulSoup libaray, extract the response content and store it in the info variable.
- Utilizes the find and find_all functions of BeautifulSoup to navigate the HTML structure and extract the tabular data.
- Use a python for loop to systematically go through the website's content.
- Initially, I extract the column names and create a dataframe using them. In the next step, I extract all the data and append it to the dataframe.
- Gathered detailed information for the top 200 movies to ensure a comprehensive dataset.
- Transform the dataframe into a CSV file for enhanced usability.
-  The structured dataset is ready for immediate use in data analysis, visualization, unlock valuable insights about movies effortlessly. 
