# MEAN LOCAL DEVELOPMENT App

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.1.

## Pre-requisites

Rename the file called `nodemon.json.example` to `nodemon.json`. That file will hold your Database and JWT Key credentials. You will also need to connect the Database of your choice in `app.js` where I used MongoDB and Mongoose. 

## Development server

FRONT END Angular
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

BACKEND NodeJs-Nodemon
Run `npm run start:server` for a dev server for the backend. 

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
