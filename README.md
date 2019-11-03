# Streamy Server - A Node.js API CRUD server

## What it is

The Streamy server is a simple Node.js server setup with the json-server module installed which allows us to use a json object as a database to receive all of the CRUD operations a traditional API server would have.

## Installation

* To to use this web-app server first start by making sure you have Node.js installed.

* Using `npm -i` install the dependencies required in both the client and server directories

* using two terminal windows run `npm start` in both the client and server directories

* visit `http://localhost:3000/` in your browser to start the web-app

### A typical top-level directory layout

    .
    ├── client              # The Streamy client
    └── server              # This project
> Mak sure to download both projects and use npm start on the server before starting the client

## CRUD Operations

### Read

The read operation uses the StreamList compoent to fetch a list of all possible streams that can be viewed by a visitor.

![Image of Read Operation](https://github.com/tekgeek88/project-image-repo/raw/master/crud-base-project-client-starter-react/read.png)

### Create

The create operation uses the StreamShow component to allow users to click on the hyperlinked title of a stream and view more detailed information for the given stream.

![Image of Create Operation](https://github.com/tekgeek88/project-image-repo/raw/master/crud-base-project-client-starter-react/create.png)

### Update

The update operation uses the StreamEdit component to fetch and pre-fill a form relating to the given stream. The user is able to edit fields and submit a patch request via the submit button to the backend api in order to update information for the given stream.

![Image of Update Operation](https://github.com/tekgeek88/project-image-repo/raw/master/crud-base-project-client-starter-react/update.png)

### Delete

The delete operation uses a re-usable modal in order to confirm and issue delete requests to the backend api in order to delete the given stream.

![Image of Delete Operation](https://github.com/tekgeek88/project-image-repo/raw/master/crud-base-project-client-starter-react/delete.png)

## References

Please visit Stephen Grider's Udemy course to learn more about how this web-app was designed and built.

https://www.udemy.com/share/101WcY/

## Licensing

Copyright 2019 Carl Argabright

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

## Contact

If you have any comments or suggestions please feel free to leave them for me on
GitHub

If you need to say something a little more personal feel free to send me an
email at carl.argbright@gmail.com