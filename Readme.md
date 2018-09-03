UI Application Excercise
------------------------
- Create a simple registration screen
- Call a Mock API on submission of data
- HTML5, CSS and JS to be used
- Please place all your files within src folder.
- Any client side MVC can be used
- If Node.js is used, please add one node task as a script in package.json
- Any testing framework libraries can be used


To Run the Project
==================

- this is angular 5 project, generated using ng-cli.
- `npm install` to install dependencies from registry.npmjs.org
- `ng serve --open` to open the project at localhost:4200. If port is occupied, use `ng serve --port <port_number>` to modify the port
- to deploy on a web server, say tomcat, use `ng build` to package the application. This creates 'dist' folder. Copy the contents of 'dist' folder to the root scope of the tomcat webapps directory

Specifications
===============
- 'package.json' has all node dependencies for the angular project
- 'tslint.json' has linting specifications
- 'index.html' has bootstrap css
- 'main.ts' is entry point for angular `AppModule`, which imports various modules(like BrowserModule, FormsModule, etc), declares various components used in the project, provides services and boots Angular app.
- 'app.routing' contains all route links mapping to various components
- 'index.ts' in each component folders contains definitions for all exports.
- there are mainly 3 components - 1.login  2.home  3.register
- there are mainly 3 services - 1.authentication  2.alert  3.user service(for CRUD operations)
- fake backend provider HTML5 local storage for storing registered user data and provides fake authentication and CRUD methods; and uses the Angular 2 MockBackend to replace the default backend used by the Http service, and intercept http requests and provide fake responses
- 'user.ts' has `User` model for user properties
