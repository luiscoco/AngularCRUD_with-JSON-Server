# CrudApp

The video explaining the source code is available in the URL: https://www.youtube.com/watch?v=4mKY_yDq64g

1.Install the project dependencies running the command:
```
npm install
```
or 
```
npm i
```

2.Install the JSON-Server(https://www.npmjs.com/package/json-server) globally, running the command:
```
npm i -g json-server
```

3.Run the JSON-Server with the command:
```
json-server --watch db.json
```

4.Finally, to run the application run the command:
```
ng serve-o
```

5.In the source code there is a db.json file in the root directory to initialize with values the server.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
