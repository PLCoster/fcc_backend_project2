# Free Code Camp: Backend Project 2 - Request Header Parser Microservice

## Request Header Parser Microservice

The aim of this project was to build a small web app with functionality similar to: https://request-header-parser-microservice.freecodecamp.rocks/

The project was built using the following technologies:

- **HTML**
- **JavaScript** with **[Node.js](https://nodejs.org/en/) / [NPM](https://www.npmjs.com/)** for package management
- **[Express](https://expressjs.com/)** web framework to build the web API.
- **[Bootstrap](https://getbootstrap.com/)** for styling with some custom **CSS**
- **[FontAwesome](https://fontawesome.com/)** for icons
- **[nodemon](https://nodemon.io/)** for automatic restarting of server during development.

### Project Requirements:

- **User Story #1:** A request to `/api/whoami` should return a JSON object with your IP address in the `ipaddress` key.

- **User Story #2:** A request to `/api/whoami`should return a JSON object with your preferred `language` in the language key.

- **User Story #3:** A request to `/api/whoami` should return a JSON object with your software in the `software` key.

### Project Writeup:

The second Free Code Camp: Back End Development Project is a request header parser API. Users can receive information about their request headers by:

- Sending a `GET` request to `/api/whoami` returns the ip address, language and software used to make the request, in JSON format.

### Project Files:

- `index.js` - the main entry point of the application, an express web server handling the routes defined in the specification.

- `public/` - contains static files for the web app (stylesheet, logo, favicons etc), served by express using `express.static()`.

- `views/` - contains the single html page for the web app, `index.html`, which is served by express on `GET` requests to `/`.

### Usage:

Requires Node.js / NPM in order to install required packages. After downloading the repo, install required dependencies with:

`npm install`

A development mode (with auto server restart on file save), can be started with:

`npm run dev`

The application can then be viewed at `http://localhost:3000/` in the browser.

To start the server without auto-restart on file save:

`npm start`

# Request Header Parser Microservice BoilerPlate

The initial boilerplate for this app can be found at https://github.com/freeCodeCamp/boilerplate-project-headerparser/

Instructions for building the project can be found at https://www.freecodecamp.org/learn/back-end-development-and-apis/back-end-development-and-apis-projects/request-header-parser-microservice
