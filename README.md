# Basic angular app

This is a basic setup of an angular app with karma/protractor for testing.

## Installation

* Fork the repo
* Rename the app name in the **package.json** and the **bower.json**
* Run `npm install`
* Run tests using `npm test`

Struggling with Protractor? Do this
`npm install -g protractor`
`webdriver-manager update —standalone` (that’s two hyphens before `standalone`)
`webdriver-manager start —standalone` (two hyphens, obv)

Then in a separate tab - keeping this server running
`npm run protractor`

You also need a third tab with
`npm start`

If you had to do `sudo` when installing npm run `sudo chown -R $(whoami) ~/.npm` so you don’t have to use sudo in the future.
