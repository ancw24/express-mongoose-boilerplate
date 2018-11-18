# Express + Mongoose + Bootstrap + FontAwesome

This boilerplate uses [Express](http://expressjs.com/), [Mongoose](http://mongoosejs.com/), [Bootstrap 4](https://getbootstrap.com/), [Font Awesome 5](https://fontawesome.com/), [jQuery](http://jquery.com/), [Axios](https://github.com/axios/axios) and more useful stuff. We included everything you need to start a small project from scratch.

The demo application includes a ToDo list with a mongoose model, a controller and the needed JavaScript for handling events and loading data with Axios.

The `npm start` command will not only start the application, but also watch for changes of your SCSS and JavaScript files, using [webpack](https://webpack.js.org/). The [nodemon](https://nodemon.io/) package is used to automatically restart the server, if your scripts change, while it's running.

## Installation

1. Download the boilerplate as .zip-file.
1. Extract the files and copy them to your project root.
1. Run `npm install` in your terminal to get all needed packages.
1. Copy **the .env.sample** file to **.env**.
1. Run `npm start` to start the node.js application.

## Development &amp; Production mode

If you want to run the application in development mode, where webpack is watching for changes of SCSS and JavaScript files, etc. simply run the following command:  
`npm run dev`.

And for production mode use:  
`npm start`

## Configuration

The configuration of the basic application (environment + port) is done in the **.env** file.  
If you need more settings, that you would like to exclude from Git, you should add them here.

If you want to use TLS for secure connections, read our [Let's Encrypt](./docs/Lets-Encrypt.md) page.

## Routing

The routing is done in the **/routes/web.js** file.  
Just edit it and make it fit to your needs.

## Views

The views are located in the **/views/** directory and we use [Pug](https://github.com/pugjs/pug) as the default template engine.

## Navigation

The navigation items are red from the **helpers.js** file. If you don't want to use the helper file you can overwrite the navigation in the view file **partials/navbar.pug**.

### Watching for changes

The **npm run dev** command will recompile all SCSS and JavaScript files automatically using webpack, if changes are detected.

## License

This project is available under [MIT License](./License.md) and is free for private and commercial usage.
