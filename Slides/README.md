Important info from Reveal.js

## Installation

The **basic setup** is for authoring presentations only. The **full setup** gives you access to all reveal.js features and plugins such as speaker notes as well as the development tasks needed to make changes to the source.

### Basic setup

The core of reveal.js is very easy to install. You'll simply need to download a copy of this repository and open the index.html file directly in your browser.

1. Download the latest version of slides files

3. Open index.html in a browser to view it


### Full setup

Some reveal.js features, like external markdown, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

3. Navigate to the folder with reveal.js files

4. Install dependencies
```
$ npm install
```

5. Serve the presentation and monitor source files for changes
```
$ grunt serve
```

6. Open <http://localhost:8000> to view your presentation

You can change the port by using `grunt serve --port 8001`.

## License

MIT licensed

Copyright (C) 2013 Hakim El Hattab, http://hakim.se
