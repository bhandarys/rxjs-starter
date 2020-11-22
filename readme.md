1. mkdir rxjs
2. cd rxjs
3. npm init
4. npm install rxjs webpack webpack-dev-server typescript ts-loader
5. npm install webpack-cli --save-dev

In package.json: add the following line to the scripts

"start": "webpack-dev-server --mode development"

Copy the webpack.conig.js and tsconfig.json from this folder

Create your index.html, css/style.css, src/code.ts

To clone:
git clone https://github.com/bhandarys/rxjs-starter.git

Run
1. npm install
2. npm start

Reference: 
https://www.youtube.com/watch?v=PhggNGsSQyg

( This youtube video uses yarn while I have used npm for this starter pack )