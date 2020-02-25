# Buy and Sell used educational items at school

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0.

This project is chosen because of the problem students faces of getting books or other study-related
stuff from seniors. It also shares the news of various university clubs. 

##How To Start:
1. First clone this project and open it in any IDE.
2. Clone the project "Minor-7 Server".
3. Run 'npm start' command in terminal of both.
4. Run Mongodb server. To do that first go to the MongoDB\Server\3.4\bin directory and then use mongod command.
If your data is not stored at default data/db (which is in C drive if you are using windows) then you can use
 mongod --dbpath yourpath/data/db  command.

##Update the dependncies:
npm i -g npm-check-updates
npm-check-updates -u
npm install
## pre-requisites:
1. node `v6.10+`
2. npm `v4.5+`
3. mongo `v3.4.3+`

### few conventions followed:

1. For a particular module, 
    1. All services are grouped under `_services` folder    
    2. All models are grouped under `_models` folder
    3. All pipes are grouped under `_pipes` folder

2. If a module has default component, then it is kept under `__MODULENAME` folder

    Example: `login-register` module has default component placed under `__login-register` folder

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
