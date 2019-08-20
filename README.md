# newsScraper
News Scraper

This is a web app that lets users view and leave comments on the latest news. It uses Mongoose and Cheerio to scrape news from another site.

Whenever a user visits the site, the app scrapes stories from a news outlet and displays them for the user. Each scraped article is then saved to the application database. The app scrapes and displays the following information for each article:
Headline - the title of the article
Summary - a short summary of the article
URL - the url to the original article

Users are also able to leave comments on the articles displayed and revisit them later. The comments are saved to the database as well and associated with their articles. Users are able to delete comments left on articles. All stored comments are visible to every user.

Technologies used: 
express
express-handlebars
mongoose
cheerio
axios
Heroku
mLab: a remote MongoDB database that Heroku supports natively.