# VSCode TypeScript Scratchpad

A simple setup for TypeScript coding in VSCode, with compile and debugging.

## Prerequisites

To start, **[node](https://nodejs.org)** is required.

The TypeScript Compiler (tsc) is required in your path, install globally:

via **npm**
```
    npm -g install typescript
```

via **[yarn](https://yarnpkg.com)**
```
    yarn add global typescript
```

## Getting started

Fork the repo and clone to your local machine, open a terminal / command line and get base packages:

via **npm**
```
    npm install
```

via **yarn**
```
    yarn
```

The src/index.ts is your entry point, code away! Add additional files to the src folder and import to your src/index.ts file to use per the hello_world example.

## Adding 3rd Party Packages

Open a terminal / command line, add a package:

via **npm**
```
    npm install packageName --save
```

via **yarn**
```
    yarn add packageName
```

If typings are missing/not included with the base packge, the majority of popular npm packages have typings defined on npm under the @types scoping.

Install typings as a dev dependancy:

via **npm**
```
    npm install @types/packageName --save-dev
```

via **yarn**
```
    yarn add @types/packageName -D
```

Both steps can be completed in one setup by using [typac](https://github.com/ewgenius/typac)

Install typac globally:

via npm
```
    npm install -g typac
```

via yarn
```
    yarn add global typac
```

Install a package using the typac command:

e.g.
```
   typac moment
```

typac installs moment as a dependancy and @types/moment as a dev dependancy, via npm or yarn if you have it installed.

## Building

Running the Build task in VSCode will compile TypeScript (/src) to es2015 JavaSript (/dist).

Shortcut on Windows/Linux: Ctrl + Shift + B, macOS: Command + Shift + B

## Debugging

Set breakpoints in your Ts code and press F5 to start the debugger, happy debugging!

## Live feedback

Ts imports will work out of the box with [Quokka.js](https://quokkajs.com)

## Running

To run the your code

via **npm**
```
    npm start
```

via **yarn**
```
    yarn start
```

This command uses ts-node to run your application in node using your tsconfig.json compile options, without compiling to JavaScript files.

## Customisations

For editor defaults, adjust editor.config.

To change Ts linting, adjust tslint.json.

Adjust the settings in tsconfig.json to change the compiled output.
