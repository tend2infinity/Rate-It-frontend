# RateIt!
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
### A Real-world online movie rating app where you can nominate your favourite movies and get them to the top of the leaderboard! 

### 🔗 Live Demo

The website is Hosted [Here](https://rate-it-project.netlify.app)

Front-end [Repository](https://github.com/tend2infinity/Rate-It-Project)

Back-end [Repository](https://github.com/savi-1311/Rate-It-Backend) (Do check out this repository as well!)

***
__Special Mention:__ [TMDB API](https://developers.themoviedb.org/3) for providing the amazing database of movies.
## Main Features
### Landing Page
The landing page gives us a brief introduction about this app. Anyone can Signup if its a new user or login if its an old one. The syling of all the pages inside the app is done using "styled-components". AOS library (animate on scroll) is used to animate the content while scrolling!
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit1.JPG)
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit2.JPG)
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit3.JPG)

### Authentication
Firebase authentication service is used for signin and signup features using email, username and password .
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit5.JPG)

### Top Navbar
Once you are logged in, the top navbar will contain your username and three different buttons for navigation namely "Nomination", "Leaderboard" and "Logout".
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit6.JPG)

### Movie-List
All the logged in users are directed to the movie list page where you can browse different movies from different categories . The movie name, a short description and the release date is also visible in that card. All these results are fetched from "TMDB API". You can obviously nominate any movie using the nominate button and if its already nominated, you can remove it from your nominations. Once you nominate a movie the "movieID" and the "user" is registered into our mongoDb database. The same movie cannot be nominated twice, if anyone does that then a toast will get displayed showing "Already nominated"!
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit7.JPG)
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit9.JPG)

### Movie Tralier
Every movie card has a "Watch Traler" button using that you can view the trailer of that movie which is available on youtube . This feature is implemented using "movie-trailer" package.
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit8.JPG)

### Movie Search
You can search your favourite movie in the search box and nominate that as well!
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit14.JPG)

### My Nominations
Every user is allowed to nominate atmost five movies and the nominated movies can be viewed in the "Nomination" Tab. If you try to nominate more than five movies then a toast is displayed showing "Already nominated". You can obviously remove those movies which you do not wish to have in that list. A toast appears every time you add or remove a movie .
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit11.JPG)

### Leaderboard
The leaderboard contains the top voted movies by our community which is sorted in descending order of votes.
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit12.JPG)
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit13.JPG)

### Footer
The footer of every page contains developer contact, so that for any bug anyone can reach us immediately!
<br>
![](https://github.com/tend2infinity/Rate-It-Project/blob/master/public/screenshots/rateit3.JPG)


***
### Tech Stack and Concepts used:

<p align="left"> <a href="https://expressjs.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/expressjs/expressjs-ar21.svg" alt="express" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://heroku.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg" alt="heroku" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank"> <img src="https://img.icons8.com/color/48/000000/html-5.png"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> <img src="https://img.icons8.com/color/48/000000/javascript.png"/> </a> <a href="https://www.mongodb.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/mongodb/mongodb-icon.svg" alt="mongodb" width="50" height="50"/> </a> <a href="https://nodejs.org" target="_blank"> <img src="https://img.icons8.com/color/48/000000/nodejs.png"/> </a> <a href="https://postman.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a> <a href="https://www.netlify.com" target="_blank"> <img src="https://www.netlify.com/img/press/logos/logomark.png" alt="Netlify" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1280px-React-icon.svg.png" alt="React" width="60" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank"> <img src="https://firebase.google.com/downloads/brand-guidelines/PNG/logo-logomark.png" alt="Firebase" width="30" height="40"/> </a> <a href="https://material-ui.com" target="_blank"> <img src="https://material-ui.com/static/logo.png" alt="Material UI" width="50" height="60"/> </a></p>
<br>

* __Frontend:__ Reactjs, Javascript, MaterialUI, Slick-Slider, HTML, CSS, Styled-components
* __Backend:__ Firebase, Nodejs, Expressjs
* __Databse:__ MongoDB
* __Deployment:__ Heroku, Netlify
* __Tools:__ Git

***

### Setting Up the Project 🔧

* __Frontend__

1. Clone the repo

   ```sh
   git clone https://github.com/tend2infinity/Rate-It-Project
   ```
2. Install NPM packages

   ```sh
   npm install
   ```
3. Create a .env file using the template .env.template and add values accordingly.

* __Backend__

1. Clone the repo

   ```sh
   git clone https://github.com/savi-1311/Rate-It-Backend
   ```
2. Install NPM packages

   ```sh
   npm install
   ```
3. Create a .env file using the template .env.template and add values accordingly.
   
### Usage

1.  Switch to the Backend folder and run the backend server

    ```sh 
    npm start 
    ```
    
2.  Switch to the Frontend folder and run the frontend server

    ```sh 
    npm start 
    ```
    
    Make sure you start the Backend server before the Frontend server to avoid unnecessary errors.
***

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://portfolio-shambhavi.netlify.app/"><img src="https://avatars.githubusercontent.com/u/56017960?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Shambhavi</b></sub></a><br /><a href="https://github.com/tend2infinity/Rate-It-Project/commits?author=savi-1311" title="Code">💻</a> <a href="#design-savi-1311" title="Design">🎨</a> <a href="https://github.com/tend2infinity/Rate-It-Project/commits?author=savi-1311" title="Documentation">📖</a> <a href="#data-savi-1311" title="Data">🔣</a></td>
    <td align="center"><a href="https://github.com/tend2infinity"><img src="https://avatars.githubusercontent.com/u/61948033?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Somya S. Singh</b></sub></a><br /><a href="https://github.com/tend2infinity/Rate-It-Project/commits?author=tend2infinity" title="Code">💻</a> <a href="#design-tend2infinity" title="Design">🎨</a> <a href="https://github.com/tend2infinity/Rate-It-Project/commits?author=tend2infinity" title="Documentation">📖</a> <a href="#content-tend2infinity" title="Content">🖋</a></td>
    <td align="center"><a href="http://abhi-blogs.web.app"><img src="https://avatars.githubusercontent.com/u/36303692?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Abhishek Garain</b></sub></a><br /><a href="#mentoring-abhi211199" title="Mentoring">🧑‍🏫</a> <a href="https://github.com/tend2infinity/Rate-It-Project/pulls?q=is%3Apr+reviewed-by%3Aabhi211199" title="Reviewed Pull Requests">👀</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
