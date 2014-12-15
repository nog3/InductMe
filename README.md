InductMe is a hackerspace written induction tool based on the Hackerthon Starter Nodejs boilerplate.

Getting Started
---------------

The easiest way to get started is to clone the repository:

```bash
# Get the latest snapshot
git clone --depth=1 https://github.com/nog3/InductMe.git

cd InductMe

# Install NPM dependencies
npm install

node app.js
```

:exclamation: **Note:** I highly recommend installing [Nodemon](https://github.com/remy/nodemon).
It watches for any changes in your  node.js app and automatically restarts the
server. Once installed, instead of `node app.js` use `nodemon app.js`. It will
save you a lot of time in the long run, because you won't need to manually
restart the server each time you make a small change in code. To install, run
`sudo npm install -g nodemon`.

Please note you will also need a local mongodb instance running, mongoose will create the collection automatically.
