# Restaurant Webpack Website

A simple website that uses npm and webpack in development to achieve bundled js file. Also use here ES6 modules (import and export) that really made the code cleaner. Especially when combined with factory methods and module methods.

## Getting Started

As this is a simple web app it doesn't need any special installation. Just run the index.html file inside the dist folder and website will load.

### Prerequisites

Clone ths repo, https://github.com/ryecoder/restaurant-webpack-live,

```
git clone https://github.com/ryecoder/restaurant-webpack-live
```

### Installing

I use Visual Studio code for coding and running a live server with hot reload. But you can run the index.html file on your browser and manually reload the browser if it is more preferred. To run in Visual Studio code.

Install this plugin in Visual Studio Code

```
Name: Live Server
Id: ritwickdey.liveserver
Description: Launch a development local Server with live reload feature for static & dynamic pages
Version: 5.6.1
Publisher: Ritwick Dey
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer
```

Once installed, open your repo clone folder. With the index.html file open, right click and then click run with live server.

For development, run `npm install` in the command line inside the repo clone to install dependencies. `npm run build` run script to run the webpack bundler.

One thing I notice, when you have an transpiling error (error like duplication of use of variable names that webpack detects) with your code you will notice nothing will happen. Even if you check your developer tools in your browser no message will output. A simple way I found (not checked the internet for an efficient one) is to run `npx webpack` manually. This will log out in console whats happening in your code. Then you will see where the error in your code is.

## Built With

- npm
- Webpack
- ES6
- Vanilla JS
- CSS
- Html

## Authors

- **Ryanell Maniego**

## Acknowledgments

- The Odin Project
