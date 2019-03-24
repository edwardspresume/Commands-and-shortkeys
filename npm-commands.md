# NPM Commands


&nbsp;


### NPM
| Description                    | Command                                      |
| ------------------------------ | -------------------------------------------- |
| NPM help info                  | `npm \| npm help`                            |
| Get npm version                | `npm -v/--version`                           |
| Install lastest version of npm | `npm i/install -g npm@latest`                |
| Install lastest unofficial version of npm | `npm i -g npm@next`               |


&nbsp;


### NPM Init config
| Description                    | Command                                      |
| ------------------------------ | -------------------------------------------- |
| Create package.json            | `npm init \| npm init -y`                    |
| Assign an author to the init | `npm config set init-author-name [YOUR NAME]`  |
| Assign a license to the init | `npm set init-license [License name]`          |
| Get the author of the package | `npm config get init-author-name`             |
| Get the license of the pacakge | `npm get init-license`                       |
| Remove the license of the package | `npm delete init-license`                 |
| Remove the author of the package | `npm config delete init-author-name`       |


&nbsp;


### Packages

| Description                    | Command                                      |
| ------------------------------ | -------------------------------------------- |
| Install a package globaly      | `npm i -g [package name]`                    |
| Install a package locally      | `npm i [package name]`                       |
| Install package and save as a dependency | `npm i [package name] -d/--save`   |
| Install package and save as a dev dependency | `npm i [package name] -D/--save-dev`   |

## INSTALLING LOCAL PACKAGES

- npm install lodash --save (or npm install --save lodash)

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
