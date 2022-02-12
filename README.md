## Project Name
restaurantData

## Table of Contents
- [Description & General Info](https://github.com/briennekordis/restaurantData#description--general-info)
- [Languages & Technologies](https://github.com/briennekordis/restaurantData#languages--technologies)
- [Setup & Use](https://github.com/briennekordis/restaurantData#setup--use)
- [Suggestions for Improvement](https://github.com/briennekordis/restaurantData#suggestions-for-improvement)
- [Licensing Information](https://github.com/briennekordis/restaurantData#licensing-information)

## Description & General Info
This project uses GraphQL to Create, Read, Update, and Delete (CRUD) restaurant data (in JSON format). 

## Languages & Technologies
- JavaScript 
- GrapghQL

## Setup & Use
0. Prerequisite: Make sure you have Node installed on your computer
1. Download or clone the index.js file
2. Open up Terminal (OSX)/or equivielent command line and navigate to the directory of the index.js file
3. run `npm install` from the command line
4. run `node index.js` from the comman line
5. navigate to localhost:550/grapghql in your browser to open up the GrapghQL Playground connected to the index.js file
6. Paste the code from the grapghql file in this directory into the editor on the left side of the GraphQL Playground
7. Click on the "Play" arrow button in the GraphQL Playground to run the different mutations. The returned data will appear on the right side of the screen. 
  - You can make changes to the editor on the left side, such as changing the name passed into the editRestaurants mutation and then run the getRestaurants mutation with the "Play" button again to see your changes to the data
  - Note: If you make any changes to the index.js file, you will have to stop your local server and reload your browser for the GraphQL Playground to update accordingly. 

## Suggestions for Improvement
- Currently, the restraurants data is stored as a variable within the index.js file. While this allowed the project to work easily in the GrapghQL Playground, it would be advisable to seperate the data into a JSON file to clean up the index.js file. 

## Licensing Information
This code was written for the MITxPro's Full Stack Developer Course.

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
