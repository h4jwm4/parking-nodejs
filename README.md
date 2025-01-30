## Parking in Nodejs
A parking booking web app made in node js.
Users can pre book their parking slots with the help of this web app.

## Built With

This application is built on nodeJS, typed in javascript. Vanilla html-css-js is used to built the frontend.

## Requirements

For development, you will only need Node.js and a node global package, npm, installed in your environement.

### Node

-   #### Node installation on Windows

    Just go on [official Node.js website](https://nodejs.org/) and download the installer.
    Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

-   #### Node installation on Ubuntu

    You can install nodejs and npm easily with apt install, just run the following commands.

        $ sudo apt install nodejs
        $ sudo apt install npm

-   #### Other Operating Systems
    You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

    $ npm install npm -g

###

---

## Installation

    $ git clone https://github.com/codehackerone/parkify
    $ cd parkify
    $ npm install

### Configure environmental variables

Create a `.env` file then edit it with your settings. You will need:

-   ENV=development
-   PORT=[your_port]
-   MONGO_URI=[your_mongo_uri]
-   JWT_SECRET=[your_jwt_secret]
-   EXPIRY=[your_jwt_expiry_time]
-   SECRET=[your_secret_for_mongostore]
-   CLOUDINARY_CLOUD_NAME=[your_cloudinary_cloud_name]
-   CLOUDINARY_KEY=[your_cloudinary_key]
-   CLOUDINARY_SECRET=[your_cloudinary_secret]
-   MAPBOX_TOKEN=[your_mapbox_project]
-   X_RAPIDAPI_HOST=[your_rapidapi_sendgrid_host]
-   X_RAPIDAPI_KEY=[your_rapiapi_sendgrid_key]
-   SENDGRID_EMAIL=[no-reply@your_domain.com]

### Running the project

    $ npm start
        or
    $ npx nodemon

---
