Tyler McGinnis' React Fundamentals course

npm run create builds the webpack dist folder, etc.

package.json script:     
  "start": "webpack-dev-server --open"
  loads server and opens a Chrome tab and allows hot-loading new content!
  (Webpack watches files and if there is a change, babel-loader compiles to js and React will display it.)
