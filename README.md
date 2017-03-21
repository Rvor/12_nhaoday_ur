nhaoday.vn
1. install webpack
npm install webpack babel-loader babel-core babel-preset-es2015 babel-preset-react --save-dev
2. install express
npm install express --save
3. install react
npm install react react-dom --save-dev
4. Use webpack to build 
webpack ./client/index.js ./bundle.js --module-bind 'js=babel-loader?{"presets": ["es2015","react"]}'
5. Add webpack config
touch webpack.config.js
6. install less and loader
npm install less less-loader style-loader css-loader --save-dev
7. install babel-cli
npm install babel-cli -g
8. install extract-text-webpack-plugin
npm install extract-text-webpack-plugin --save-dev
9. install express-handlebars
npm install express-handlebars --save
10. install redux
npm install redux react-redux --save