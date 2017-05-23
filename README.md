# Nodejs-with-Socket.io

**Source code** for [
Create a character voting app using React, Node.js, MongoDB and Socket.IO]().

This project is developed by Sahat Yalkabov in
(http://sahatyalkabov.com/create-a-character-voting-app-using-react-nodejs-mongodb-and-socketio/),
I am uploading it in my repository to show the design pattern that I am following in Node.js ,React.js, MongoDB,
Express.js and Socket.io application development.

# Setup

1 - git clone https://github.com/AliMol/Nodejs-with-Socket.io.git

2 - cd into installed folder : Nodejs-with-Socket.io

3 - run NPM install or YARN install

4 - run NPM START

5 - in a new CMD window run gulp or npm run watch

5 - copy newedenfaces.bson into ~\Program Files\MongoDB\Server\{version number}\bin

6 - cd into ~\Program Files\MongoDB\Server\{version number}\bin

7 - run mongorestore newedenfaces.bson -d nef -c characters in a new CMD window
this command will restore the bson file into mongo db

8 - run mongod in the previous CMD window
this command will start up Mongo DB

you can see the application on http://localhost:3000

....