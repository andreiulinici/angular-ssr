# angular-ssr

This app is using Server-side rendering, based on https://angular.io/guide/universal

## Prepare

### Install the Express Engine for running Angular Apps on the server for server side rendering.

`ng add @nguniversal/express-engine --clientProject angular-ssr`


## Start rendering your app

`npm run build:ssr && npm run serve:ssr` or simply `npm run build`

This will start a HTTP server. Open your browser on http://localhost:4000 URL which should serve HTML rendered on the server.

You can now use server.js with pm2 or forever.js to run in background forever.


Other Angular Server-side rendering:
https://itnext.io/server-side-rendering-ssr-in-angular-5-the-simplest-and-quickest-ssr-approach-34cf53224f32


_________________________________

# Default Angular readme

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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
