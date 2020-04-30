

# Description
To create a webpage using HTML and SCSS for the attached site.
The goal of this assigment is to learn about CSS positioning, Grid layout, SCSS features like variables, mixins, inheritance, loops, functions, math operations etc.

## Installation

1. Navigate to project directory 
2. Change the scripts in package.json file to
    "scripts": {
    "sass": "./node_modules/.bin/node-sass styles/main.scss dist/main.css"
     },
    "devDependencies": {
    "node-sass": "^4.13.1",
    "sass": "^1.25.0"
  } 
3. Run `npm run sass`.

Note: npm should be pre-loaded using commands npm i(to install) and npm init(to initiate)

## Requirements
-> Have a web browser installed in your machine (chrome,safari..etc) 
-> github link

## Technologies Used
    * HTML5
    * CSS3
    * SASS - SCSS

## Build
Default build mode is `production`. This will build `assignment4.html` and `main.css` files in the `dist` directory.
1. To build the app, run `npm run build`.
2. Launh the app by opening the file `./dist/assignment4.html` in a browser.

## Development Server
Follow below steps to lauch the app using 
1. Run command - npm run sass.
2. Live server app can be used to launch thereby.

## License
[MIT License](https://opensource.org/licenses/MIT)



