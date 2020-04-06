# MERN stack Jogging Track app

### Functionalities of this application
* User Authentication based on user roles(admin, manager, user)
* Regular user would only be able to CRUD on their owned records, a user manager would be able to CRUD users, and an admin would be able to CRUD all records and users.
* Each time entry when entered has a date, distance, and time.
* When displayed, each time entry has average speed.
* Filter by dates from-to.
* Report on average speed & distance per week.
* REST API. Make it possible to perform all user actions via the API, including authentication
* All actions need to be done client side using AJAX, refreshing the page is not acceptable.

### Need knowledge
* JavaScript is a MUST to extend this application now that ReactJS is a framework of JavaScript.
* The basic of ReactJS knowledge is required to understand this application.
* The concept of Redux for JavaScript is required how to manage states in its store.

## Prerequisites
Make sure you have installed all of the following prerequisites on your development machine:
* Git - [Download & Install Git](https://git-scm.com/downloads). OSX and Linux machines typically have this already installed.
* Node.js - [Download & Install Node.js](https://nodejs.org/en/download/) and the npm package manager. If you encounter any problems, you can also use this [GitHub Gist](https://gist.github.com/isaacs/579814) to install Node.js.
* MongoDB - [Download & Install MongoDB](http://www.mongodb.org/downloads), and make sure it's running on the default port (27017).

```bash
$ npm install
```

```bash
$ npm start
```
Go to your web browser and you are able to find the app running on localhost port 3000

