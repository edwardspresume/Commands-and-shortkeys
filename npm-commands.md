# NPM Commands

## GET VERSION

- npm -v (or --version)
- npm install -g npm@latest
- npm i -g npm@next

## GET HELP

- npm help
- npm

## CREATE PACKAGE.JSON

- npm init
- npm init -y (or --yes)

## SET DEFAULTS

- npm config set init-author-name "YOUR NAME"
- npm set init-license "MIT"

## GET DEFAULTS

- npm config get init-author-name
- npm get init-license

## REMOVE DEFAULTS

- npm config delete init-author-name
- npm delete init-license

## INSTALLING LOCAL PACKAGES

- npm install lodash --save (or npm install --save lodash)
- npm install moment --save
- npm install gulp gulp-sass --save-dev

## INSTALL GLOBAL MODULE

- npm install -g nodemon
- npm install -g live-server

## INSTAL DEPENDENCIES

- npm install
- npm install --production

## REMOVING MODULES

- npm un (or uninstall) gulp-sass --save-dev
- npm rm (or remove) gulp --save-dev

## INSTALL CERTAIN VERSIONS

- npm install lodash@4.17.3 --save

## UPDATE

- npm update lodash --save
- npm update -g

## RUN NODEMON

- nodemon

## FIND ROOT FOLDER

- npm root -g

## REMOVE GLOBAL PACKAGES

- npm remove -g nodemon

## LISTING PACKAGES

- npm list (or ls)
- npm list --depth 0
- npm list -g --depth 1

## Files

- rm -rf <Folder name> (remove folder)
- nano <file name>

## INSTALL NODMON LOCALLY

- npm install live-server --save-dev

## NPM SCRIPT

"scripts": {
"sass": "node-sass -w scss/ -o css/",
"build-css": "node-sass --include-path scss scss/main.scss build/css/style.min.css",
"build-js": "browserify js/\*\*.js>build/js/script.min.js",
"build": "npm run build-css && npm run build-js",
"watch": "npm nodemon -e js,scss -x \"npm run build\" --ignore build/"
}
