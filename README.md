# Mission to Mars

![NASA Image](https://github.com/kntln/Mission-to-Mars/blob/main/figures/mars_exploration.png)


## Overview of the Project
For this project, a web application was built to showcase the gathered data about the mission to mars from all over the web. A python script was written to scrape new data from websites with a click of a button. In addition, a mongo database was used to store the data and lastly a Web Framework named Flask was used to create the website.

## Procedure
### Web Scraping
Web scraping 
- Chrome Developer Tools were used to identify the HTML components of the websites for scraping. 
- BeautifulSoup and Splinter were used to automate the scrape.

![Web Scraping](https://github.com/kntln/Mission-to-Mars/blob/main/figures/web_scraping.png)

### Store the Data
- The data gathered from scraping were then stored in a Mongo Database.

![Storing the Data](https://github.com/kntln/Mission-to-Mars/blob/main/figures/store_data.png)

### Web Application
- Using Flask, the web application will have a button that executes the scraping and as well as updates the page with the newest data. See the image below for the completed website.

![Web Site](https://github.com/kntln/Mission-to-Mars/blob/main/figures/website.png)





