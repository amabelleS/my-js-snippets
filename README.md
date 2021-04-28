# my-js-snippets ❤️

This Application was developed with typescript, react, redux, node.js, express, lerna and more.
Implementing Esbuils - An extremely fast JavaScript bundler.
You can Check there documentation over here: [Esbuild docs](https://esbuild.github.io/)

## About this project ❤️

A node cli that start a web service with addvance javascript sandbox.
The tool enables the user to write ES-07 code (or text snipets) in the browser,
showing the results in a preview window and saving them to the local file system.
started as an expriment for learning typescript (with react and redux) and implementing Esbuils -
An extremely fast JavaScript bundler. Also, managed mono-repo with lerna.

### The cli commands ❤️

start my-js-snippets server with npx:

```bash
npx my-js-snippets serve
```

#### When installed globally you can run those command:

Serve on port 4005 (defualt):

```bash
my-js-snippets serve
```

You can provide a file name:

```bash
my-js-snippets serve your-file-name.js
```

Define a specific port to run the server on:

```bash
my-js-snippets serve --port 4200
```

Different variations:

```bash
my-js-snippets serve your-file-name.js --port 4200
```

```bash
my-js-snippets serve -p 4200
```

```bash
my-js-snippets your-file-name.js serve -p 4200
```
