
# Basics of Node.js and NPM

## Initializing package.json

cd into the directory and run

```
npm init
```
Follow along the prompts and answer the questions as follows: accept the default values for most of the entries, except set the entry point to index.html.
<br>
-This should create a package.json file in your folder.

## Installing an NPM Module

-Install an NPM module, lite-server, that allows you to run a Node.js based development web server and serve up your project files. To do this, type the following at the prompt:

```
npm install lite-server --save-dev
```

-Now if you will open package.json it will look like this:

```

  "name": "git-test",
  "version": "1.0.0",
  "description": "This is the Git and Node basic learning project",
  "main": "index.html",
  "scripts": {
    "start": "npm run lite",
    "test": "echo \"Error: no test specified\" && exit 1",
    "lite": "lite-server"
  },
  "repository": {
    "type": "git",
    "url": "git+https://jogesh_k_muppala@bitbucket.org/jogesh_k_muppala/git-test.git"
  },
  "author": "",
  "license": "ISC",
  "homepage": "https://bitbucket.org/jogesh_k_muppala/git-test#readme",
  "devDependencies": {
    "lite-server": "^2.2.2"
  }
}
```

## start the development server by using

```
npm start
```

-This should open your index.html page in your default browser.
-If you now open the index.html page in an editor and make changes and save, the browser should immediately refresh to reflect the changes.

Note: add **node_modules to git ignore


