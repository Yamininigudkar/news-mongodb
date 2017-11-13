# The New York Time Scraper

### Overview

The news-mongodb (New York Times Scraper) is a scraper app which captures the title, summary and image of articles of The New York Times. In this app, users are able to save their preferred articles, add notes and edit notes to one or multiple articles. 

In this repository, you can see source code of NYT Scraper. For experiencing, please go to Heroku:

https://agile-hamlet-63972.herokuapp.com/saved

### Key Dependencies

`request`: enables `cheerio` to get access to front-end code of https://www.nytimes.com/section/world

`cheerio`: scrapes front-end code from https://www.nytimes.com/section/world

`mongoose`: be in charge of database of `NYT Scraper`

`express`: builds server-side routes and functions

`morgan`: logs server-side requests, helping debugging

`express-handlebars`: a powerful front-end builder without requiring multiple html pages

`body-parser

##Instructions

*Make sure you have fulfilled the prerequisites above.
*Clone this repository with git clone https://github.com/Yamininigudkar/news-mongodb 
*Install modules with npm install
*Run node server.js
*Go to localhost:3000 in your web browser.
