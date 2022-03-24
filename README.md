# A basic React project with linting

# Libraries

This project uses [semistandard](https://github.com/standard/semistandard) which is itself based off of
[standard](https://standardjs.com/).

# How to get a project to this state:

# Key steps:

## Install semistandard

You can install the `semistandard` npm package with:

    npm install semistandard --save devr`

## Update `package.json` with to use semistandard commands

    ...
    "scripts": {
      ....
      "lint": "semistandard --env jest",
      "format": "semistandard --fix --env jest"
    },
    ...

## Update your edittor with the appropriate plugin

Follow: [the standard js instructions](https://standardjs.com/#are-there-text-editor-plugins) for instructions for your environment.

## Profit

You can now run lint manually from a terminal with `npm run lint` to see errors and `npm run format` to attempt to fix errors. If you
also added a plugin for your code editor, your editor should also tell you when there are lint errors automatically.

## Additonal config

Even though this project uses the `semistandard` package, the configuration options are the same as for standard so you
can get additional information about how to do things and supported flags at the standard [website](https://standardjs.com/).
