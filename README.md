# Stock Simple

## Table of contents
1. [Description](#description)
2. [Technology](#technology)
3. [Installation](#installation)
4. [Usage](#usage)

## Description

Full Stack web application that provides a simple and intuitive tool for engaging with the stock market. Users can sign up, track stocks, set up watchlists, test investment strategies, and view the latest market news. 

## Technology

- [Cheerio](https://www.npmjs.com/package/cheerio)
- [Express Web Server](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose ORM](https://mongoosejs.com/)
- [Node.js](https://nodejs.org/en/)
- [Passport.js](http://www.passportjs.org/)
- [React.js](https://reactjs.org/)
- [Robot 3T](https://robomongo.org/)
- [Yarn Package Manager](https://yarnpkg.com/lang/en/)

# Installation 
1. Using the link in the [technology](#technology) section above, download the Robot 3T client.
2. Go into your Robo 3T client and create a database called 'stockSimple'. 
3. Clone the repository to your local machine. 
```bash
git clone https://github.com/DavidLapadula/stock-simple.git
cd stock-simple
``` 
4. Install dependencies with the following command. 
```bash
yarn install
``` 
5. Run the following command to seed the database. 
```bash
yarn populate
```
6. This will create a test account with the email 'test@email.com' and the password 'testpassword'.
7. Go to [World trading data](www.worldtradingdata.com) and get a free API key. 
8. Create a .env file in the root directory of the proect and add `WORLDTRADINGDATA_API_KEY=<yourapikey>`. 
9. Run the following command in the root directory and your site will open on http://localhost3000. 
```bash
yarn start
```

## Usage

### Login
![Login Gif](mdImages/loginVid.gif)

### Track stocks with watchlists
![Watchlist Gif](mdImages/watchlistVid.gif)

### View the latest news
![Visit article Gif](mdImages/articleVisitVid.gif)

### Search for stocks and save articles
![Save Article](mdImages/saveArticleGif.gif)

### Test and track your investments
![Login Gif](mdImages/addStockVid.gif)


