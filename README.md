![CF](http://i.imgur.com/7v5ASc8.png)
=================================================

## Lab 14
### Chris Merritt
### Links and Resources
* [PR]()

[![Build Status](https://www.travis-ci.com/401-advanced-javascript-merritt/lab-14.svg?branch=master)](https://www.travis-ci.com/401-advanced-javascript-merritt/lab-14)

### Modules
#### `testroutes.js`
Contains the additional routes created to test the different authorization roles & permissions of create, read, update, delete.


Usage Notes or examples
### Setup
#### `.env` requirements
* `npm i`
* `PORT` - 3000
* `MONGODB_URI` - required
#### Running the app
* `nodemon`

* Endpoint: `/public-stuff`
  * Accessable for anyone, regardless of login status.

* Endpoint: `/hidden-stuff`
  * Accessable for only users who have logged in.

* Endpoint: `/something-to-read`
  * Accessable for only those who have read permissions.

* Endpoint: `/create-a-thing`
  * Accessable for only those with create permissions.

* Endpoint: `/update`
  * Accessable for only those with update permissions.

* Endpoint: `/jp`
  * Accessable for those authorized and with update permissions.

* Endpoint: `/bye-bye`
  * Accessable for only those with delete permissions.

* Endpoint: `/everything`
  * Accessable for superusers.
  
#### Tests
* How do you run tests?
  * `npm run test`
  * `npm run lint`
