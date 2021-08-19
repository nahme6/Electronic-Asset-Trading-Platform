# CAB302-Electronic-Asset-Trading-Platform

This GitHub directory contains our group's submission for CAB302's major project (Semester 1, 2021). The setup instructions from our documentation are included below. These instructions have been confirmed to work on Windows devices, but have not been tested on other operating systems.

Start by downloading the zip file and extracting all its content.

## Setup Instructions

### Client
1. Download and install Node.js and the bundled npm package manager.
2. Run the runClient.cmd file in the [root directory](https://github.com/dtayl147/CAB302-Electronic-Asset-Trading-Platform/tree/main) of the codebase. This file will automatically download all required external dependencies, compile the JavaScript client, start the client on port 5000 and open the webapp in the computer's default web browser.

OR

2. Open the command prompt.
3. Use `cd` to navigate to the [client_side_app](https://github.com/dtayl147/CAB302-Electronic-Asset-Trading-Platform/tree/main/client_side_app) directory of the codebase.
4. Enter `npm install` to download all required external dependencies.
5. Enter `npm install -g serve` to install the serve dependency.
6. Enter `serve -s build` to compile and start the client.
7. Open a web browser of your choice and connect to [http://localhost:5000](http://localhost:5000).

### Server
1. Download and install MariaDB, setting the root account username and password to `root` and `root` respectively.
2. Host the MariaDB server on port 3306.
3. Run the runServer.cmd file in the root directory of the codebase. This file will automatically download all required external dependencies, compile the Java server, and run the server, hosting it on port 8080 with a connection to the MariaDB server on port 3306.

OR

3. Open the command prompt.
4. Use `cd` to navigate to the [root directory](https://github.com/dtayl147/CAB302-Electronic-Asset-Trading-Platform/tree/main) of the codebase.
5. Enter `mvnw spring-boot:run` to download all required external dependencies, compile the Java server, and run it.
