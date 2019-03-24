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


## FIND ROOT FOLDER

- npm root -g

## REMOVE GLOBAL PACKAGES

- npm remove -g nodemon

## LISTING PACKAGES

- npm list (or ls)
- npm list --depth 0
- npm list -g --depth 1


| Description                    | Command                                      |
| ------------------------------ | -------------------------------------------- |
| Update packages if update availabe | `npm update`                             | 
| Check if a package is outdated | `npm outdated`                               | 
| update all global packages     |`npm update -g`                               | 
| see which global packages need to be updated | `npm outdated -g --depth=0`    | 
| update a single global package |`npm update -g <package_name>`                | 
