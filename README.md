#### Faselty Landing Page

#### Installation

[Gulp] is used as a task manager for some tasks like Sass and Haml.

Make sure that [node.js] and [npm] are installed.

Install Node packages

```
npm install
```

##### Build

This will build all the files to the `/build` directory, this directory contains the final files to be pushed to the server.

```
gulp build
```

##### Development mode

This will start the development mode and initialize a [localhost:3000] server to preview and watch file changes as you code, but make sure you run `gulp build` first.

```
gulp serve
```

#### Icons
Icons generated from [fontello] and could be used as:

``` haml
%i{class: "icon-facebook"}
%i{class: "icon-twitter"}
%i{class: "icon-pinterest"}
```

[Gulp]:http://gulpjs.com/
[node.js]:https://nodejs.org/
[npm]:https://www.npmjs.com/
[localhost:3000]:http://localhost:3000/
[fontello]: http://fontello.com/
