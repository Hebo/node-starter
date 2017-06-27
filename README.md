# Node.JS Starter Template

Forked from [express-babel](https://github.com/vmasto/express-babel) with love.


### Features:
- [Express.js](https://expressjs.com/) as the web framework.
- Linting with [ESLint](http://eslint.org/).
- Testing with [Jest](https://facebook.github.io/jest/).
- [Quick deployment guide](DEPLOYMENT.md) for Heroku, AWS Elastic Beanstalk, and App Engine.

## Getting started

```sh
# Install Yarn
npm install -g yarn

# Install dependencies
yarn
```

Then you can begin development:

```sh
yarn start
```

This will launch a [nodemon](https://nodemon.io/) process for automatic server restarts when your code changes.

### Testing

Testing is powered by [Jest](https://facebook.github.io/jest/). This project also uses [supertest](https://github.com/visionmedia/supertest) for demonstrating a simple routing smoke test suite. Feel free to remove supertest entirely if you don't wish to use it.

Start the test runner in watch mode with:

```sh
yarn test
```

You can also generate coverage with:

```sh
yarn test -- --coverage
```

(the extra double hyphen `--` is necessary).

### Linting

Begin linting in watch mode with:

```sh
yarn run lint
```
