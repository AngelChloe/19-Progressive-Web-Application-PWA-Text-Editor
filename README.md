# 19-Progressive-Web-Application-PWA-Text-Editor


## Description

The application is a web text editor where the user can create notes or code snippets with or without an internet connection and where the user can reliably retrieve them for later use.  The integrated service worker and Cache API's ensure that the application will remain fully functional even without and active internet connection.  This application allows the user to access visited pages even if the application is offline.


## Table of Contents

1. [Acceptance Criteria](#acceptance-criteria)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Screenshots](#screenshots)
5. [Heroku](#heroku)
6. [GitHub Link](#github-link)
7. [References](#references)
8. [Author and Acknowledgements](#author-and-acknowledgements)

## Acceptance Criteria

- GIVEN a text editor web application
- WHEN I open my application in my editor
- THEN I should see a client server folder structure
- WHEN I run `npm start` from the root directory
- THEN I find that my application should start up the backend and serve the client
- WHEN I run the text editor application from my terminal
- THEN I find that my JavaScript files have been bundled using webpack
- WHEN I run my webpack plugins
- THEN I find that I have a generated HTML file, service worker, and a manifest file
- WHEN I use next-gen JavaScript in my application
- THEN I find that the text editor still functions in the browser without errors
- WHEN I open the text editor
- THEN I find that IndexedDB has immediately created a database storage
- WHEN I enter content and subsequently click off of the DOM window
- THEN I find that the content in the text editor has been saved with IndexedDB
- WHEN I reopen the text editor after closing it
- THEN I find that the content in the text editor has been retrieved from our IndexedDB
- WHEN I click on the Install button
- THEN I download my web application as an icon on my desktop
- WHEN I load my web application
- THEN I should have a registered service worker using workbox
- WHEN I register a service worker
- THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
- WHEN I deploy to Heroku
- THEN I should have proper build scripts for a webpack application


## Installation

- This text editor require a number of methods and store data to an IndexedDB database to be builded up.

- This application will require the installation of Node.js and various npm packages.
 
- Node Package Manager (npm) is a software manager and installer which puts the modules in place so that the node project can utilize it, and also, it manages dependency conflicts intelligently and initialized using **npm init**. The package.json will be generated and will contains all the details of the application in which the user have inputted during the npm initialization. 

- This application will use the following npm packages:-

     * npm install express (express.js)
     * npm install --save-dev webpack (Webpack)
     * npm install webpack-dev-server --save-dev (webpack-dev-server)
     * npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
     * npm install babel (Babel)
     * npm install --save-dev css-loader (CSS-loader)
     * npm install concurrently --save (run multiple commands concurrently.) (Concurrently)
     * npm install idb (IndexedDB)

* The required modules are bundled in the package.json file and at CLI or integrated terminal type in **npm run install**, the modules will be installed.       

## Usage

- npm start or nodemon
- http://localhost:3000/ from browser

## Screenshots

Text Editor
![TextEditorHome](https://user-images.githubusercontent.com/105569378/198852383-f79e2554-b0b9-4e6e-8ca9-800669c465df.png)

** App Manifest Application
![App Manifest Application](https://user-images.githubusercontent.com/105569378/198852386-cc3f652a-77bb-4055-ba09-4964dfbcdd6d.png)

Service Worker
![Service Worker](https://user-images.githubusercontent.com/105569378/198852402-4efc6495-e692-498b-bf93-a202725418b9.png)

IndexDB JATE
![IndexDB_JATE](https://user-images.githubusercontent.com/105569378/198852404-d3317c3d-388a-4d92-8c0a-51ac6febb044.png)


## Heroku
🚀 [Deployed Link](https://damp-reaches-38127.herokuapp.com/)


## References:

*   The Unit Ahead : Progressive Web Applications (PWA)
    Module 19 Mini-Project: Deploy Contact Directory App on Heroku with Script
*   Request-Response : The Full-Stack Blog : Heroku Deployment Guide
*   Google
 
## Author and Acknowledgments:

Created by Univertiy of Utah Coding Bootcamp Student, Cindy Chynoweth with the help of other AMAZING developer's out there​



