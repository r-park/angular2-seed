[![Build Status](https://travis-ci.org/r-park/angular2-seed.svg?branch=master)](https://travis-ci.org/r-park/angular2-seed)


# Angular2 Seed

- Angular `2.0.0-alpha.46`
- BrowserSync
- ES6 Shim
- Gulp `4.0.0-alpha.1`
- Jasmine
- Karma
- Typescript
- SASS
- SystemJS

## Installing dependencies
```bash
npm install
```

#### Gulp v4 (optional)
```bash
npm install -g gulpjs/gulp-cli#4.0
```
The gulp tasks require gulp v4-alpha. If you don't wish to globally install the v4 gulp-cli, you can run the gulp tasks using the locally installed gulp under `./node_modules/.bin` — for example:
```bash
./node_modules/.bin/gulp test
```

## Gulp Tasks
#### Developing
```bash
$ gulp
```
Executing the default `gulp` command will:
- Build the project
- Start the **BrowserSync** server at <a href="http://localhost:3001" target="_blank">localhost:3001</a>
- Watch for changes to the source files and process changes

#### Testing
```bash
$ gulp test.watch
```
Executing `gulp test.watch` will:
- Run the test suites
- Watch for changes to the source files
- Re-run the tests whenever the sources are modified

For a single test run without auto-watch, execute `gulp test` instead.
