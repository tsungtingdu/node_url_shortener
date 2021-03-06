## URL Shortener

This is a web app build with Node.js, Express.js, and MySQL database.

In this app,

1. You can create a short url by putting in the original long url
2. You can retrive the same shor url if you put in the same original (long) url
3. You will see an error message if you try to use an invalid short url

---
### Getting Started
#### Prerequisites/Environment
* Node.js v10.15.0
* body-parser:^1.19.0
* connect-flash: "^0.1.1
* express: ^4.17.1
* express-handlebars: ^3.1.0,
* express-session: ^1.16.2,
* method-override: ^3.0.0,
* mysql2: ^1.6.5
* nodemon: ^1.19.1
* sequelize: ^5.10.3
* sequelize-cli: ^5.5.0

#### Clone this project
```
$ git clone https://github.com/jacs0110/node_url_shortener.git
```
#### Setup the app

1. Go to the project folder **node_url_shortener**

2. Install npm packages
```
$ npm install
```

4. Create MySQL database with name "url_shortener"

5. Run db:migrate
```
$ npx sequelize db:migrate
```

6. Run the server
```
$ npm run dev
```
and you will see "Listening on http://localhost:3000" in the console

---
### Authors
[Jacs](https://github.com/jacs0110)

*I'm now learning web development and want to become a software engineer in the future. Feel free to let me know if you have any feedback or questions about my project. Thanks!*