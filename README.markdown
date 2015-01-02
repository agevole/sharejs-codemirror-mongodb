sharejs.codemirror.example
==========================

This repo was forked from charlieRobert's repo. It's goal is to make persistent documents rather than storing everything in a livedb.

This way, documents aren't reset on a server restart.

It uses Mongo instead.

##Installation and Use##

1. clone this repo
2. make sure you have Mongo

###Server###

1. start mongo with `mongod` in terminal
2. run `node index.js`

###Client###

1. Open a browser and launch `127.0.0.1:8007` substituting a port number you passed as an argument when starting the server if needed.
2. Open another tab and launch the same url
3. Type some JavaScript into the codemirror instances. They should be synced.