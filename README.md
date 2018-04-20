#     Friend Finder Application
# 
##     Description
## 
	*Friend Finder* implements friend matching based on the user's
responses to a ten question survey. The user responds to questions
with values from 1 (Strongly Disagree) to 5 (Strongly Agree). When
the survey is submitted, an existing user record closest to the
current user's responses is found and returned. The closest set of
user responses is defined as the set with the lowest absolute
difference for all ten questions combined.

	*Friend Finder* application is meant to simulate a simple dating
app. The application is implemented using a
[Node.js](https://nodejs.org/en/) and
[Express](https://expressjs.com/) server on the back end and the
CSS framework on the front
end.

##     Demo
## 
	*Friend Finder* is deployed to Heroku. Please check it out
[here](https://immense-sierra-78314.herokuapp.com/survey).

##     Installation
## 
	To install the application follow the instructions below:

	git clone git@github.com:zschneid85/friend-finder.git 
	cd
	friend-finder npm install

##     Running Locally
## 
	To run the application locally and access it in your browser,
first set the `PORT` environment variable to the value of your
choice. An example is shown below.

		export PORT=5000

	After the `PORT` environment variable has been set, run the
Node.js application with the command below.

		node server.js

	The application will now be running locally on `PORT`, in this
case that is port 5000. You can then access it locally from your
browser at the URL `localhost:PORT`, in this case `localhost:5000`.





# node-js-getting-started

A barebones Node.js app using [Express 4](http://expressjs.com/).

This application supports the [Getting Started with Node on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs) article - check it out.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku CLI](https://cli.heroku.com/) installed.

```sh
$ git clone git@github.com:heroku/node-js-getting-started.git # or clone your own fork
$ cd node-js-getting-started
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
$ heroku create
$ git push heroku master
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Documentation

For more information about using Node.js on Heroku, see these Dev Center articles:

- [Getting Started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Heroku Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Best Practices for Node.js Development](https://devcenter.heroku.com/articles/node-best-practices)
- [Using WebSockets on Heroku with Node.js](https://devcenter.heroku.com/articles/node-websockets)
