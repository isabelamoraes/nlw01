<h1 align="center">
  <br>
    <img src="https://github.com/isabelamoraes/nlw01/blob/master/demo/logo.jpg?raw=true" alt="Ecoleta">
  <br>
  <br>
  ECOLETA
</h1>

<h4 align="center">
  Register and find collection points for recycling
</h4>

<p align="center">
  <a href="#features">Features</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#getting-started">Getting Started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#reference">Reference</a>
</p>

<p align="center">
  <img alt="Web Application Demo" src="https://github.com/isabelamoraes/nlw01/blob/master/demo/ecoleta.gif?raw=true" width="70%">
  <img alt="Mobile Application Demo" src="https://github.com/isabelamoraes/nlw01/blob/master/demo/ecoleta_app.gif?raw=true" width="23%">
</p>

## Features

This project was developed with the following technologies:

-  **[Expo](https://expo.io/)** - A platform for making universal native apps for Android, iOS, and the web with JavaScript and React.
-  **[React JS](https://reactjs.org/)** - A JavaScript library for building user interfaces.
-  **[Node JS](https://nodejs.org/)** - A runtime enviroment for JavaScript applications.

## Getting Started

To clone and run this application, place from your command line:

```bash
# Clone this repository
$ git clone https://github.com/isabelamoraes/nlw01.git nlw01

# Go into the repository
$ cd nlw01/server

# Install dependencies
$ npm install

# Create server database
$ yarn knex:migrate
$ yarn knex:seed

# Run the server application
$ npm run dev

# Go into the repository desired
$ cd nlw01/web
# OR
$ cd nlw01/mobile

# Install dependencies
$ npm install

# Run the application
$ npm start

# For cache error
$ npm cache clean --force
```

## Reference

This application was developed during my participation in Next Level Week 01, promoted by Rocketseat.

