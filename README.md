<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Node.js_logo.svg/1200px-Node.js_logo.svg.png" width=400 height=200> <img src="https://upload.wikimedia.org/wikipedia/commons/6/64/Expressjs.png" width=450 height=150>

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE) [![Node.js](https://img.shields.io/badge/Node-v6.11.3-blue.svg)](https://nodejs.org/) [![NPM](https://img.shields.io/badge/NPM-v6.4.1-blue.svg)](https://www.npmjs.com/) [![Express](https://img.shields.io/badge/Express-tested-brightgreen.svg)](https://expressjs.com/) [![Morgan](https://img.shields.io/badge/Morgan-tested-brightgreen.svg)](https://www.npmjs.com/package/morgan) [![Path](https://img.shields.io/badge/Path-tested-brightgreen.svg)](https://nodejs.org/api/path.html) [![Nodemon](https://img.shields.io/badge/Nodemon-tested-brightgreen.svg)](https://www.npmjs.com/package/nodemon) [![Serve-Favicon](https://img.shields.io/badge/Serve--Favicon-tested-brightgreen.svg)](https://www.npmjs.com/package/serve-favicon)

## Setting up an express server using node.js ##
This is the default source code for a bare-bones express server running on node.js. This code was written for the proposes of providing a basic template to allow simple plug & play usage and easy scaleability for adding multiple webpages for routing REST requests. This code will be changed for various reasons including but not limited to adding/deleting routes, modules, etc.

* [Getting Started](#getting-started)
  * Main Application File
  * Routing
    * Static Files
* [Prerequisites](#prerequisites)
  * Install Node.js
  * Install NPM
* [Installation](#installation)
* [Built With](#built-with)
  * Express
  * Morgan
  * Path
  * Nodemon
  * Serve-Favicon
* [License](#license)

### Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. These instructions will help you deploy your code to localhost and also view logs of REST requests received by express for debugging purposes. See prerequisites & installation for notes on how to deploy the project on a live system.
* Main Application File: server.js
* Routing: All requests go through /*
  * Static Files(Javascript, CSS, Imgs, etc.): go through /static/*

### Prerequisites ###
* Install Node.js - You must have [Node.js](https://nodejs.org/en/download/) installed on your local system. Download the Node.js source code or a pre-built installer for your operating system.
* Install NPM
  * Download the [Package Manager](https://www.npmjs.com/get-npm)
  * Double click on the package and follow steps to install.

### Installation ###
* Open terminal and ```cd``` into the root folder of the project.
* Run ```npm install``` to install all of the node modules(project dependencies) that are needed.
* Testing and Debugging
  * [Local Development Server](https://nodejs.org/en/docs/guides/getting-started-guide/)
    * run the `npm run dev` command from the directory that contains your servers main application file.
      * Optional: after the `npm run dev` command, type a port # to host off of.
    * In your preferred web browser, go to http://localhost:PORT.

### Built With ###
* [Express](https://expressjs.com/) - The web framework used.
* [Morgan](https://www.npmjs.com/package/morgan) - HTTP request logger middleware function.
* [Path](https://nodejs.org/api/path.html) - Provides utilities for working with file and directory paths.
* [Nodemon](https://www.npmjs.com/package/nodemon) - Automatically restarts the application when file changes in the directory are detected.
* [Serve-Favicon](https://www.npmjs.com/package/serve-favicon) - Middleware for serving a favicon.

### License ###
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.
- - - -
_a project by [Gurvinder Singh](https://github.com/gurvinder)_
