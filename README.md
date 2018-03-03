# SQL QUERY

SELECT TOP 1000 [p_id]
      ,[date]
      ,[vch_url]
  FROM [ActivityTracker].[dbo].[ActivityTable]


SELECT COUNT (DISTINCT [vch_url]) as URLCount
  FROM [ActivityTracker].[dbo].[ActivityTable] 
  where vch_url like '%MicroUI%' and p_id='BZE' and date>='2007-05-01 00:00:00' and date<='2007-05-15 00:00:00'

SELECT [vch_url], *
  FROM [ActivityTracker].[dbo].[ActivityTable] 
  where vch_url like '%MicroUI%' and p_id='SAP' and date>='2007-05-06 00:00:00' and date<='2007-05-15 00:00:00'



# CustomDirective

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
