# gadget-angular5    [![Build Status](https://travis-ci.org/dodash/gadget-angular5.svg?branch=master)](https://travis-ci.org/dodash/gadget-angular5)
scaffold for angularj5 app

# An OpenSocial Gadget Written In Angular5

## Intro
This is an example project for creating an opensocial gadget for hosting in an opensocial container.This project is embedded with angular5 lib
with simple "Welcome to Angular5 App!" app.

## Steps 
First install the necessary dependencies, this may take a few minutes.
```
npm install
```
Install the angular-cli dependencies (if not installed), this may take a few minutes.
```
npm install -g @angular/cli
```
Start a Development Server
```
ng serve --open
```
You can now access the gadget or execute standalone angular5 app from http://localhost:4200 (opens automatically in browser) and you see "Welcome to Angular5 App!" getting displayed.

Once application is ready, create a production build by running
```
ng build
```

This will create production copy of application. you will be able to "dist" directory. move "gadget.xml" present under "src" directory to "dist" directory. now, you can copy "dist" directory to any web server and run it.

## Adding to an Open Social Container (dashboard)
To add this gadget to an open social container, specify the URL to the gadget.xml file served by this Angular application, e.g.
http://localhost:4200/gadget.xml. If you change the host/port, make sure you edit the gadget.xml accordingly e.g http://localhost:4200.
