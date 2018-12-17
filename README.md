# web-pack-notes


add script in package.json ,

     "crun" :"webpack-dev-server --content-base dist"

To run build minified code on ./dist folder --content-base should be defined. 

     "build": "webpack --mode production",
     "start": "webpack-dev-server --mode development --open"
     
when npm start is run it created compiled files but files are not created inside ./dist folder as it aims to render page fast on browser ,
to create files inside dist folder crun script ( as mentioned in point 1) should be used.



Some useful link for webpack ::
https://www.freecodecamp.org/forum/t/running-webpack-and-webpack-dev-server/19361
