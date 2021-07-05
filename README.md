# Mission-to-Mars
Web scraping project.

## Overview
Use BeautifulSoup, Splinter, and Pandas to scrape four different webpages related to Mars, and display the results on a webpage using MongoDB and Flask.

### Scrape Mars Data
We performed scraping on various websites realted to Mars Mission, Data, Facts and Images. We used Jupyter Notebook and Python for web scraping. We extracted the Mars News,
Mars Images, Mars and Earth Facts Table, and images of Mars Hemispheres.
Scraped Mars URLs
![](https://github.com/ysbcode/Mission-to-Mars/blob/main/Resources/Hemisphere_URLs.PNG?raw=true)

### Using MongoDB to store the data
Once the data was scraped, we used MongoDB to store the data. Using the scraping function, the data extracted was compiled in a dictionary and stored in a MongoDB collection titled "mars_app".

### Using Flask to present our scraped data
An instance of Flask was created and a connection to the database was established. Using the connection, the scraped data is presented on the Flask website. The website UI was updated using Bootstrap.

### Screenshots
Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles
![](https://github.com/ysbcode/Mission-to-Mars/blob/main/Resources/Mobile%20Responsive_Button_Table_Image.PNG?raw=true)

Deliverable 2: Mars Hemisphere full-resolution Images
![](https://github.com/ysbcode/Mission-to-Mars/blob/main/Resources/Mars_Hemispheres.PNG?raw=true)

Deliverable 3: Mobile-friendly version with smaller screen
![](https://github.com/ysbcode/Mission-to-Mars/blob/main/Resources/Mobile_Friendly.PNG?raw=true)

Adding Style to Button
![](https://github.com/ysbcode/Mission-to-Mars/blob/main/Resources/Button_Style.PNG?raw=true)

Adding Thumbnail to Image
![](https://github.com/ysbcode/Mission-to-Mars/blob/main/Resources/Image_Thumbnail.PNG?raw=true)
