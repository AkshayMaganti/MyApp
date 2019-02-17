 - npm init -y
    creates 
- git init
    initializes empty git repo
- npm install --save-dev babel-cli
- npm install --save express
- add "server": "babel-node server/index.js" in scripts in package.json
- create .babelrc file
    {
        "presets": ["es2015"]
    }
- npm run server
    starts the server
- npm install --save-dev nodemon
    nodemon starts the server everytime we make changes to a file
    replace server value in scripts in package.json with "nodemon --watch server --exec babel-node -- server/index.js"
 -  server/index.js
    - 