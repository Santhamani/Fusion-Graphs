# Fusion-Graphs
Graphical Notation demo
How we can create dynamic charts using ExpressJS and MongoDB.

Steps
Installing Node.js
  Eg: {node
  > console.log("Hello World");
  Hello World
  
Installing ExpressJS
  Create a new directory: $ mkdir node-fusioncharts-demo
  Change to the new directory $ cd node-fusioncharts-demo
  Install express for specific application $ npm install express
  
Installing MongoDB

Populating data in MongoDB
  name of the database (-d fusion_demo)
  name of the collection (-c fuel_price)
  type of the input data (--type json)
  location of the file containing data (--file data.json)
  option to indicate input is JSON array (--jsonArray)
    $ mongoimport -d fusion_demo -c fuel_price --type json --file data.json --jsonArray
    connected to: 127.0.0.1
    2015-09-01T21:02:42.210+0530 imported 9 objects

Creating REST API for data retrieval
  Import the express and mongodb packages to be used in the application
  Connect to MongoDB instance running locally
  Implement method to fetch the data from Database
  Create express server and REST API end-point
  Launch the express app on a port
