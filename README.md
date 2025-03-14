# DelivrME - MEAN Stack Project B

| Input | Output |
| -------- | -------- |
| Location (Address)|Show restaurants nearby and amount of restaurants nearby|
|Filter restaurant categories| Show restaurants with matching categories|
|Filter restaurants menu|Show dishes of a restaurant according to category|
|Click on Dish|Add dish to shopping card (1 click => 1 item in card), show name, amount and price of item(s), sum up prices of items in card|


## Data Structures

### Classes
```// declaration
class Restaurant {
  constructor(name, category, address, phone, hours) {
    this.name = name;
    this.category = category;
    this.address = address;
    this.phone = phone;
    this.hours = hours;
  }

getMenu() {
    // code to display all dishes of a restaurant
  }

}

// define data properties outside the class definition
Class.name = “Smiley’s Pizza”;
Class.address = “Street 1”;  // and so on```




Data Structures

Classes
// declaration
class Restaurant {
  constructor(name, category, address, phone, hours) {
    this.name = name;
    this.category = category;
    this.address = address;
    this.phone = phone;
    this.hours = hours;
  }

getMenue() {
    // code to display all dishes of a restaurant
  }


}
// define data properties outside the class definition
Class.name = “Smiley’s Pizza”;
Class.address = “Street 1”;  // and so on



## Welcome to the mean stack

The mean stack is intended to provide a simple and fun starting point for cloud native fullstack javascript applications.  
MEAN is a set of Open Source components that together, provide an end-to-end framework for building dynamic web applications; starting from the top (code running in the browser) to the bottom (database). The stack is made up of:

- **M**ongoDB : Document database – used by your back-end application to store its data as JSON (JavaScript Object Notation) documents
- **E**xpress (sometimes referred to as Express.js): Back-end web application framework running on top of Node.js
- **A**ngular (formerly Angular.js): Front-end web app framework; runs your JavaScript code in the user's browser, allowing your application UI to be dynamic
- **N**ode.js : JavaScript runtime environment – lets you implement your application back-end in JavaScript

### Pre-requisites

- git - [Installation guide](https://www.linode.com/docs/development/version-control/how-to-install-git-on-linux-mac-and-windows/) .
- node.js - [Download page](https://nodejs.org/en/download/) .
- npm - comes with node or download yarn - [Download page](https://yarnpkg.com/lang/en/docs/install) .
- mongodb - [Download page](https://www.mongodb.com/download-center/community) .

### Installation

```
git clone https://github.com/linnovate/mean
cd mean
cp .env.example .env
yarn
yarn start (for development)
```

### Docker based

> ⚠️ Make sure your Docker version is 19.03.0+.

```
git clone https://github.com/linnovate/mean
cd mean
cp .env.example .env
docker-compose up -d
```

### Credits

- The MEAN name was coined by Valeri Karpov.
- Initial concept and development was done by Amos Haviv and sponsered by Linnovate.
- Inspired by the great work of Madhusudhan Srinivasa.
