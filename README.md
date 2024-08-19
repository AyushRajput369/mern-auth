# mern-auth

First Step:
-> npm install

** Install dev dependencies whenever downloading project from github as it does not have dev dependencies **

-> npm i --save-dev nodemon <!-- Run BE server automatically on save -->
-> node index.js <!--  Manual run of BE server -->

** Add .env files as they are also not present on github repo **
Backend .env file includes:
PORT=<port_number_to_run_BE_server_on>
MONGO_CONN=<mongoDB_driver_link>
JWT_SECRET=<create_BE_secret_key> <!-- add any key for your choice -->

Run Application:
-> npm start