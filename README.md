# VSCode TypeScript Scratchpad

A simple setup for TypeScript coding in VSCode, with compile and debuggging.


## Getting started

Fork the repo and clone to your local machine, open a terminal / commandline and get base packages via **npm**

```
    npm install
```

or via **[yarn](https://yarnpkg.com)**

```
    yarn
```

## Adding Packages

Open a terminal / commandline, add a package via **npm**

```
    npm install packageName
```

or via **yarn**

```
    yarn add packageName
```


If typings are missing, the majority of popular npm packages have typing defined on npm under the @types **.

To install as dev dependancies via **npm**

```
    npm install @types/packageName --save-dev
```

Via **yarn**
```
    yarn add @types/packageName -D
```


## Building

Running the Build task in VSCode will compile TypeScript (/src) to es2015 JavaSript (/dist).

Shortcut on Windows/Linux: Ctrl + Shift + B


## Debugging

Set breakpoints and press F5 to start the debugger, work through your bugs.


## Live feedback

Ts imports will work out of the box with [Quokka.js](https://quokkajs.com)


## Customisations

For editor defaults, adjust editor.config.

To change Ts linting, adjust tslint.json.

If you woudl like to change the output, adjust the settings in tsconfig.json.
