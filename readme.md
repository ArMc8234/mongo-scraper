# Mongo Scraper (Richmond Times-Dispatch Edition)

![Scraper_Demo] (./public/images/mongo_scraper_demo.gif)

https://calm-hamlet-46677.herokuapp.com/

## Technologies 
Mongo, Handlebars, Node, Express

## Summary
The RTD-Scraper makes an AJAX call to the Richmond Times-Dispatch website and scrapes recent articles. The articles are saved to a Mongo database that joins an articles model and a notes model.  Once the articles have been scraped, a user may select the bolded title of the article to open a notes field containing a title for the notes and a body.
