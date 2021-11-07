# Mission-to-Mars

## Overview and Purpose
______________________________________________

In our initial project we extracted information from websites using webscraping. In this process we used chrome developer tools to inspect the HTML and find the data we needed to gather. Using beautiful soup and splinter we wrote script using python to gather the data. We stored the data gathered in Mongo and created a web application using Flask. We are working with Robin who dreams to obtain a position with Nasa in the near future. Robin enjoys space exploration and she is constantly researching sites looking for data. Robin approached us with the idea to write a script that gathers the space exploration information she reviews with push of a button. In order to do this the information should be stored in a location to be shared with others. This task will allow Robin the freedom to continue identifying great sources of data without spending alot of time gathering the data. We created a web application that scrapes new data with a button press. We used a pyhthon script to navigate the data and store it in a Mongo Database.We also used Flask to display the findings in a web application.

## Analysis and Results
___________________________________________________

Our initial web app is completed and working great, Robin's would like to add more qualities to the web app to enhance the features. The enhancements to the web app will include images of Mars’s hemispheres. There is a site we will focus on using as our source and they have four hemisphere images that will really make our webb app stand out. My task include using BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.



### Scrape Full-Resolution Mars Hemisphere Images and Titles
_________________________________________________________________
I started by narrowing down to the most relevant sites that i research to use as the source of data.Using the DevTools I inspect the page for the proper elements to scrape. Using Splinter, Beautiful Soup, and Python to write a script Im able to pull data from the websites and store results a dictonary for later use.

<img width="484" alt="Splinter_BS_Scrape_Websites" src="https://user-images.githubusercontent.com/88467263/140651395-f5f7f68e-387c-4631-baf3-9437eafe0540.PNG">

### Update the Web App with Mars Hemisphere Images and Titles
_________________________________________________________________
We export the the results in our dictonary and update the Mongo database to modify our html file and update our webpage to contain all of the information we scraped, we use Flask to host on the web.

<img width="484" alt="Splinter_BS_Scrape_Websites" src="https://user-images.githubusercontent.com/88467263/140651401-84c4b1b8-2c8f-4278-a7e4-2e5880c18129.PNG">

### Add Bootstrap 3 Components
_________________________________________________________________

Finaly using the skills Ive obtained in HTML, CSS, and assistance from Bootstrap we add customization to our website by styling the "Scrape New Data" button. We update the facts table and add the four hemisphere images as thumbnails.


<img width="484" alt="Splinter_BS_Scrape_Websites" src="https://user-images.githubusercontent.com/88467263/140651429-e9fe223a-864a-4fc3-9b39-6b41bcf40007.PNG">

______________________________________________________

<img width="484" alt="Splinter_BS_Scrape_Websites" src="https://user-images.githubusercontent.com/88467263/140651434-baec4604-e4cb-409a-b942-ad8b0e52bcd2.PNG">



# Summary:
________________________

In conclusion I believe we created a efficient tool to effectively gather and display space exploration information with hopes of gaining attention from Nasa and other like minded explorers. This tool will give Robin the flexibility to gather even more relevant information in less time. Having the information stored in a DataBase like Mongo is helpful since it handles mesy data that isnt structed. This task will allow Robin the freedom to continue identifying great sources of data without spending alot of time gathering the data. Leveraging Flask to execute our scraped code to our website will help us standout and finally our added customization using Bootstrap enhances the functionality and look of our web page.
