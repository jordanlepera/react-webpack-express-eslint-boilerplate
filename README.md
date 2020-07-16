# react-webpack-express-eslint-boilerplate
My react.js boilerplate configured with Webpack, Babel, Eslint that provide clean dev and prod environment and a custom express server

# Features
* A clean development and production environment
  * A custom and optimized webpack configuration and express.js server configuration for each environment
* Transpilation with Babel
* Hot module reloading
* Testing with jest and enzyme
* Linting set up properly with ESLint following good coding practices and Prettier

# Structure
```
.
├── __mocks__
├── public
│   └── index.html
├── src
│   ├── components
│   ├── css
│   ├── server
│   │   ├── server-dev.js
│   │   └── server-prod.js
│   └── index.js
├── .babelrc
├── .gitignore
├── package.json
├── webpack.dev.config.js
├── webpack.prod.config.js
└── webpack.server.config.js
```

# Usages

For classic development usages
```
yarn dev
```

For development build
```
yarn buildDev
```

For production build
```
yarn buildProd
```
Production build will be located in ./dist/

For executing build (after production or development build)
```
yarn start
```

For launching test
```
yarn test
```

For launching coverage audit
```
yarn coverage
```
Generated coverage data will be located in ./coverage

# Author
Jordan LE PERA