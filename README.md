# Deploy LWC OSS App with Express API Server to Heroku

This repo has the sample code that shows you how an LWC OSS App that uses an Express API Server can be deployed to Heroku.

## Steps and Changes Explained

[Watch this Quick Take](https://www.youtube.com/watch?v=WHD5VZVabNw) to learn about the tweaks you need to make to your code to deploy your app to Heroku.

## Changed Files

- [`/src/server/api.js`](./src/server/api.js) to include code that serves static content. 
- `serve` script in [`package.json`](./package.json) to initialize only one Express Server.

## How to start?

Start simple by running `yarn watch` (or `npm run watch`, if you set up the project with `npm`). This will start the project with a local development server.

The source files are located in the [`src`](./src) folder. All web components are within the [`src/client/modules`](./src/modules) folder. The folder hierarchy also represents the naming structure of the web components. The entry file for the custom Express configuration can be found in the [`src/server`](./src/server) folder.
