sharejs.codemirror.example
==========================

This repo was forked from charlieRobert's repo. It's goal is to make persistent documents rather than storing everything in a livedb.

This way, documents aren't reset on a server restart.

It uses Mongo instead.

##Installation and Use##

###Server###

Using Git:

1. After cloning the repo, run `npm install` in its top level
2. To launch the server, run `node .` in the top level. You can optionally pass a port to run on with the `-p` argument

Using NPM:

1. Create a directory for the project and `cd` into it
2. Run `npm install share.js.codemirror.example` to install
3. Run `node node_modules/share.js.codemirror.example` to start the server. You can optionally pass a port to run on with the `-p` argument

###Client###

1. Open a browser and launch `127.0.0.1:8007` substituting a port number you passed as an argument when starting the server if needed.
2. Open another tab and launch the same url
3. Type some JavaScript into the codemirror instances. They should be synced.