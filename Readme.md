1. create a folder with the name of the application
2. yarn init in the workspace
3. yarn add webpack webpack-cli -D
4. create a src folder in the workspace and add index.js file in the folder
5. add

   "scripts": {
   "start": "webpack --mode development",
   "build": "webpack --mode production"
   }

   in package.json

6. yarn start
7. yarn build
8. Set up react and babel
9. yarn add react react-dom
10. yarn add babel-core babel-loader babel-preset-env babel-preset-react -D
11. create webpack.config.js file
12. then create .babelrc to provide options for the babel-loader
13. create index.html in src folder
14. yarn add html-webpack-plugin -D
15. use html-webpack-plugin in webpack.config.js
16. yarn start; see index.html created in dist folder and if you open it you can see hello world in browser
