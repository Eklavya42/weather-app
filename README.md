# Weather-Application
Node.js command line application built for giving the temperature of the location which you input.


### Prerequisites

To get this project on your local machine, you need to have [Node.js](https://nodejs.org).

### Installing

Install the project by navigating to the weather-application directory( which will contain all the project files) in bash  and running



```bash
npm install
```

This will install all the necessary dependencies. 

### How To

 Main functionality of the application will be shown here.
 To see the help, run: 

```bash
node app.js --help
```
###  To find the temperature in the location input

You can see the temperature in your location by running the following command:

```bash
node app.js -a “Your Address here ”
```

'a’ is alias for address so you alternatively write like this too:

```bash
node app.js  --address “Your address here.”
```
Note that you don’t have to write your full address but your district along with state and country.
For ex – -a ‘Mayur Vihar phase-1 Delhi  110091 India’


## Built With

* [Node.JS](http://nodejs.org) - Platform
* [Yargs](http://yargs.js.org/) - Parsing command line arguments 
* [Axios](https://github.com/axios/axios) – Promise based HTTP client for the browser and node.js

## Author

* **Eklavya Chopra** 

##
##


* Thanks to Andrew Mead for creating the course [The Complete Node.js Developer Course 2.0](https://www.udemy.com/the-complete-nodejs-developer-course-2/)
