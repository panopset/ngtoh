# [Run](http://localhost:4200/heroes)


    ng serve --open



# Genesis


Leaving out the platform specific steps you need to get Angular installed on your system, and establishing the project on github.

[Create](https://angular.io/tutorial/tour-of-heroes/toh-pt0) this project:


    ng new angular-tour-of-heroes
	ng generate component heroes
	ng generate component hero-detail
	ng generate service hero
	ng generate component messages
	ng generate service message
	ng generate module app-routing --flat --module=app
	ng generate component dashboard

# Original Document:
    

# AngularTourOfHeroes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.2.0.

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
