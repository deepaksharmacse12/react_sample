# react_sample

Sample package to work out with the React (http://facebook.github.io/react/). Webpack (https://github.com/petehunt/webpack-howto)
is used for splitting app into multiple files, and for buiding the client side files. Server is in Node.js

## 1. Installation

Install the node.js (https://nodejs.org/), In the root directory

`npm install`

For installing webpack: 

`npm install -g webpack`

## 2. Invoke webpack

Switch to the root directory having `webpack.config.js` and run:

  * `webpack` for building once for development
  * `webpack -p` for building once for production (minification)
  * `webpack --watch` for continuous incremental build in development (fast!)
  * `webpack -d` to include source maps
  
For more information on webpack refer to https://github.com/petehunt/webpack-howto/blob/master/README.md

## 3. Usage

Switch to the root directory and run : 

`node server.js`

Browse to `http://localhost:8000/`

Edit the jsx files in JSX directory, you can add scrits/CSS in the Public folder.

