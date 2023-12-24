# xfarr-api

## Installation
npm:
```bash
$ npm install jer-api
```
yarn:
```bash
$ yarn add jer-api
```

## Simple to Use
## CommonJs (CJS) syntax
```js
const jerofc = require('jer-api');
```
## ECMAScript Modules (ESM) syntax
```ts
import jerofc from 'jer-api';
```

// How to call the API
jerofc.[feature].[name](parameter)
  .then(response => {
    console.log(response);
  })
  .catch(error => {
    console.error(error.message);
  });

// Example of an API call
jerofc.igstory.npmjs("xfarr-api")
  .then(response => {
    console.log(response);
  })
  .catch(error => {
    console.error(error.message);
  });

  // Example of an API call
jerofc.igdl.npmjs("xfarr-api")
  .then(response => {
    console.log(response);
  })
  .catch(error => {
    console.error(error.message);
  });

  // Example of an API call
jerofc.twittee.npmjs("xfarr-api")
  .then(response => {
    console.log(response);
  })
  .catch(error => {
    console.error(error.message);
  });

  // Example of an API call
jerofc.tiktokStalk.npmjs("xfarr-api")
  .then(response => {
    console.log(response);
  })
  .catch(error => {
    console.error(error.message);
  });
```

# Feedback
If you have any feedback, please reach out to us at xfar.dev@gmail.com
