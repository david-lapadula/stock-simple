## Stock Simple
Full Stack web application that provides a simple and inituive tool for engaging with the stock market. Users can sign up, track stocks, set up watchlists, test investment strategies, and view the latest market news. 

## Description

## Getting Started

### Dependencies

- [React.js](https://reactjs.org/)
- [Node.js](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/)
- [Robot 3T](https://robomongo.org/)
- [Mongoose ORM](https://mongoosejs.com/)
- [Express Web Server](https://expressjs.com/)
- [Passport.js](http://www.passportjs.org/)
- [Yarn Package Manager](https://yarnpkg.com/lang/en/)
    - [Cheerio](https://www.npmjs.com/package/cheerio)
    - [Request Promise](https://www.npmjs.com/package/request-promise)

### Installing
- Fork the repository and clone it into a folder on your computer. 
- Navgiate to the root directory and run 'yarn install' in the terminal'
- Go into your Robo 3T Mongo client and create a database called 'stockSimple'. 
- Navigate back to the terminal and run 'yarn populate' to seed the database. 
- You will have a test profile in the database with the email 'test@email.com' and the password 'testpassword'.
- Go to www.worldtradingdata.com and get a free API key. 
- Create a .env file and add 'WORLDTRADINGDATA_API_KEY='<yourapikey>'. 
- Run 'yarn start' in the terminal and your site will open on http://localhost3000. 

### Executing program

* Open a terminal in the root directory of the program. The application should open at http://localhost3000. 
* Step-by-step bullets
```
yarn start
```

## Previews

### Login
***

![Login Gif](mdImages/loginVid.gif)

### Track stocks with watchlists
***

![Watchlist Gif](mdImages/watchlistVid.gif)

### View the latest news
***

![Visit article Gif](mdImages/articleVisitVid.gif)

### Search for stocks and save articles
***

![Save Article](mdImages/saveArticleGif.gif)

### Test and track your investments
***

![Login Gif](mdImages/addStockVid.gif)


