# web-pack-notes


1. Add script in package.json ,

     "crun" :"webpack-dev-server --content-base dist"

2. To run build minified code on ./dist folder --content-base should be defined. 

     "build": "webpack --mode production",
     "start": "webpack-dev-server --mode development --open"
     
when npm run start command is execute, it will compile and render page on localhost server but no physical files created inside ./dist folder as webpack's hot-reloading aims to speedly and effeciently render page on browser, To create files inside dist folder 'crun' script ( as mentioned in point 1) should be used.



Some useful link for webpack ::
https://www.freecodecamp.org/forum/t/running-webpack-and-webpack-dev-server/19361
