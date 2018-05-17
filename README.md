# gofast

An application built with technologies made to go fast

### Getting started:
 1. install docker
 2. clone the repository
    - `git clone git@github.com:brewencoded/gofast.git`
 3. install the submodules
    - `git submodule init`
    - `git submodule update`
 4. Go through the "getting started" section of server until you have a running server and db
 5. Go through the getting started section of client until you finish installing dependencies
    - run the command `yarn dev` to get the client running in dev mode
 6. Open a browser
    - `localhost:3000` for the client
    - `localhost:5000` for the server

### Todo:
 - [ ] Move docker-compose logic out of server so we can package the client bundle and move it into the container
 - [ ] Serve client logic via Sanic server
 - [ ] Wrap build processes in python scripts with a good command line interface
 - [ ] Clean-up. And lots of it.
 - [ ] ???
 - [ ] Profit!