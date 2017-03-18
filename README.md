# VSCode TypeScript Scratchpad

A simple setup for TypeScript coding in VSCode, with compile and debugging.


## Getting started

Fork the repo and clone to your local machine, open a terminal / command line and get base packages

via **npm**
```
    npm install
```

via **[yarn](https://yarnpkg.com)**
```
    yarn
```

## Adding Packages

Open a terminal / command line, add a package

via **npm**
```
    npm install packageName
```

via **yarn**
```
    yarn add packageName
```


If typings are missing/not included with the base packge, the majority of popular npm packages have typing defined on npm under the @types scoping.

To install as dev dependancie:

via **npm**
```
    npm install @types/packageName --save-dev
```

via **yarn**
```
    yarn add @types/packageName -D
```


## Building

Running the Build task in VSCode will compile TypeScript (/src) to es2015 JavaSript (/dist).

Shortcut on Windows/Linux: Ctrl + Shift + B, macOS: Command + Shift + B


## Debugging

Set breakpoints in your Ts code and press F5 to start the debugger, happy debugging!


## Live feedback

Ts imports will work out of the box with [Quokka.js](https://quokkajs.com)

## Running

To run the your code

```
    npm start
```

or
```
 yarn start
```

This copmmand uses ts-node to run your application using your tsconfig.json compile options, running the code without build artifacts.

## Customisations

For editor defaults, adjust editor.config.

To change Ts linting, adjust tslint.json.

Adjust the settings in tsconfig.json to change the compiled output.
