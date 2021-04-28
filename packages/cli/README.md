start my-js-snippets server with npx:

```bash
npx my-js-snippets serve
```

# my-js-snippets ❤️

This Application was developed with typescript, react, redux, node.js, express, lerna and more.
Implementing Esbuils - An extremely fast JavaScript bundler.
You can Check there documentation over here: [Esbuild docs](https://esbuild.github.io/)

## About this project ❤️

A node cli that start a web service with advanced javascript sandbox (an interactive
coding enviroment). The tool enables the user to write ES-07 code snipets, see it excuted in
a preview window in the browser, and write comprehesive documentation using markdown. All the changes
are saved to the local file system.
started as an expriment for learning typescript (with react and redux) and implementing Esbuils -
An extremely fast JavaScript bundler. Also, managed mono-repo with lerna.

### The cli commands ❤️

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

### _About the coding enviroment_ ❤️

- Click any text cell to edit it.
- The code in each code editor is joined together into one file. If you definr a variable in cell #1, you can refer to it in ant following cell.
- You can show React components, string, number, or anything else by calling the show() function. This function is built into this enviroment.
- Re-order or delete cells using the buttons on the top right
- Add new cells by hovering on the divider between each cell
