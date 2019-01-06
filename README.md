# local-library
This repository contains code for a website for a local library. The website has entities such as books, authors and genres. The backend code is handled using the Express framework of Node.js with a MongoDB database connection. The front-end is handled using the Pug template engine. The repository is heavily based on the [tutorial code](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/forms) provided by mozilla.

# Instructions for running
0. Follow [this tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/forms) to understand the code and setup the mongodb database connection.
1. Update the username and password of the mongodb connnection in the app.js file.
2. Install the dependencies mentioned in the package.json file using [npm](https://www.npmjs.com/).
3. For running the server, use the following command in ubuntu:
 DEBUG=express-locallibrary-tutorial:* npm run devstart
