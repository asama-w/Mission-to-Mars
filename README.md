# Mission to Mars
## Project Overview
To gather information about Mars from different websites into one place by writing a script that automates the web browser with the use of BeautifulSoup and Splinter to scrap the data, then store them in MongoDB, a NoSQL database. The web application is also created using Flask to present the gathered information of the Mission-to-Mars with a feature that scrapes new data by clicking a single button, and is further customized to be mobile-responsive.

## Resources
+ **Languages:** Python3, HTML
+ **Software:** Jupyter Notebook
+ **Libraries:** BeautifulSoup, Splinter, ChromeDriverManager, Pandas, Flask, PyMongo
+ **Database:** MongoDB

## Project Description
### 1. Scraping Data (Deliverable 1)
+ Using BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and their titles.
+ _Code_: [Mission_to_Mars_Challenge.ipynb](https://github.com/asama-w/Mission-to-Mars/blob/main/Mission_to_Mars_Challenge.ipynb)

<img src= https://github.com/asama-w/Mission-to-Mars/blob/main/Additional_Images/img_url_and_titles.png width="60%" height="60%">

### 2. Updating the Web App with the scraped data (Deliverable 2)
+ Modifying `scraping.py` file with the new function that scarpe the images and titles in deliverable 1. and updating the `index.html` file to show these new information on the web application.
+ _Code_: 
  + [scraping.py](https://github.com/asama-w/Mission-to-Mars/blob/main/scraping.py)
  + [app.py](https://github.com/asama-w/Mission-to-Mars/blob/main/app.py)

**Web Application Outline before the outline customization in the following deliverable 3**

<img src= https://github.com/asama-w/Mission-to-Mars/blob/main/Additional_Images/web_app_original.png width="50%" height="50%">

**Four images of Mars Hemispheres are displayed on the web application**
<img src= https://github.com/asama-w/Mission-to-Mars/blob/main/Additional_Images/mars_hemi_outline.png width="50%" height="50%">

### 3. Customizing the Web App (Deliverable 3)
+ Modifying the `index.html` file to update the outline of the web application as well as to make it mobile-responsive.
+ _Code_: [index.html](https://github.com/asama-w/Mission-to-Mars/blob/main/templates/index.html)

#### Web App in Desktop version
The following image shows the desktop version of the web application outline after the modification.

<img src= https://github.com/asama-w/Mission-to-Mars/blob/main/Additional_Images/desktop_outline.png width="50%" height="50%">

#### Web App in Mobile version (iPhone 12 Pro)
The following image shows the mobile version (iPhone 12 pro) of the the web application outline after the modification.

<img src= https://github.com/asama-w/Mission-to-Mars/blob/main/Additional_Images/mobile_outline_1.png width="30%" height="30%"><img src= https://github.com/asama-w/Mission-to-Mars/blob/main/Additional_Images/mobile_outline_2.png width="30%" height="30%"><img src= https://github.com/asama-w/Mission-to-Mars/blob/main/Additional_Images/mobile_outline_3.png width="30%" height="30%">
