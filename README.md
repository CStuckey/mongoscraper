# GCaptain Mongoscraper

This web app allows users to scrape, save and leave comments on the latest news from gcaptain.com. Utilizing Mongoose and Cheerio, users are able to scrape news from gcaptain.com.

![Screenshot](https://user-images.githubusercontent.com/6200141/28345873-fdedbbae-6bfa-11e7-920e-69026c8857d7.png)

## User Story

1. A user visits site, the app will scrape stories from maritime news outlet [GCaptain](http://gcaptain.com/). The data will include a link to a headline. 
2. Cheerio will grab the site content and Mongoose will save it to an mLab MongoDB database.
3. All users can leave comments on the stories collected. Users are allowed to delete whatever comments they want removed. All stored comments are visible to every user.
4. A Mongoose model system is utilized to associate comments with particular articles.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Clone this repo to your desktop and run npm install to install all the dependencies.

You might want to look into config.json to make change the port you want to use.

## Deployment

After you clone this repo to your desktop, go to its root directory and run npm install to install its dependencies.

Once the dependencies are installed, you can run node server.js to start the application. You will then be able to access it at localhost:3000

This app can be found at [GCaptainScraper](https://gcaptainscraper.herokuapp.com/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
