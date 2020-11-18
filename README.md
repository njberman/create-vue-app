<h1 align="center">Welcome to create-vue-route 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/njberman/create-vue-app#readme" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="https://github.com/njberman/create-vue-app/graphs/commit-activity" target="_blank">
    <img alt="Maintenance" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg" />
  </a>
</p>

> A function to create a vuejs route with ease. Returns the object needed for the `routes` array.

### 🏠 [Homepage](https://github.com/njberman/create-vue-app#readme)

## Install

Run this in your vuejs project:

```sh
$ npm install create-vue-route
```

## Usage

In `src/router/index.js`:

```javascript
import createRoute from 'create-vue-route';
import Home from '../views/Home.vue'; // And any other views you have

const routes = [
  createRoute('/', 'Home', Home, { title: 'My Website | Home' })
  // ^^ this will return an object to define a vuejs route.
];
```

## Author

👤 **njberman**

* Github: [@njberman](https://github.com/njberman)

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2020 [njberman](https://github.com/njberman).<br />
This project is [ISC](https://github.com/njberman/create-vue-app/blob/master/LICENSE) licensed.