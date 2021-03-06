# end surveillance scorecards: angular version

Based on angular-seed project. Pulls data from [Surveillance Scorecard](https://docs.google.com/spreadsheets/d/1rTzEY0sEEHvHjZebIogoKO1qfTez2T6xNj0AScO6t24/edit#gid=1017413949) to create objects.

## below taken from angular-seed README

### Install Dependencies

We have two kinds of dependencies in this project: tools and angular
framework code.  The tools help
us manage and test the application.

* We get the tools we depend upon via `npm`, the [node package
  manager](https://www.npmjs.com/).
* We get the angular code via `bower`, a [client-side code package
  manager](http://bower.io/).

We have preconfigured `npm` to automatically run `bower` so we can
simply do:

```
npm install
```

Behind the scenes this will also call `bower install`.  You should find
that you have two new
folders in your project.

* `node_modules` - contains the npm packages for the tools we need
* `app/bower_components` - contains the angular framework files

*Note that the `bower_components` folder would normally be installed in
the root folder but
angular-seed changes this location through the `.bowerrc` file.  Putting
it in the app folder makes
it easier to serve the files by a webserver.*

### Run the Application

We have preconfigured the project with a simple development web server.
The simplest way to start
this server is:

```
npm start
```

Now browse to the app at `http://localhost:8000/app/index.html`.

