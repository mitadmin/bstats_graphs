# Production

npm install -g coffee-script

npm install

coffee -c public/\*/\*.coffee

NODE_ENV=production node server.js

# Dev

bundle

npm install -g coffee-script

npm install -g coffeescript-growl

npm install -g node-dev

npm install

foreman start
