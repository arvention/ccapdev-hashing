# ccapdev-hashing
bcrypt Tutorial for CCAPDEV1920T2

This repository will help you integrate hashing to your web applications using [bcrypt](https://www.npmjs.com/package/bcrypt). This web application is based on the previous [repository on client-side and server-side validation tutorial](https://github.com/arvention/ccapdev-validation). For this tutorial, we will use bcrypt to hash the password of the user before saving in the database.

## Contents:

Each folder and file in this repository is properly documented. You may read the `README.md` file of each folder to understand its content. You may also read the inline comments of each file explaining the statements line-per-line.

- [controllers](controllers) - This folder contains files which defines callback functions for client requests.
- [helpers](helpers) - This folder contains files which contains helper functions.
- [models](models) - This folder contains files for database modeling and access.
- [public](public) - This folder contains static assets such as css, js, and image files.
- [routes](routes) - This folder contains files which describes the response of the server for each HTTP method request to a specific path in the server.
- [views](views) - This folder contains all hbs files to be rendered when requested from the server.
- [index.js](index.js) - The main entry point of the web application.
