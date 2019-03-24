# NPM Commands


&nbsp;


### NPM
| Description                    | Command                                      |
| ------------------------------ | -------------------------------------------- |
| Find root folder               | `npm root -g`                                |
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
| Install a certain version of the package | `npm i [package Name@4.15.3]`      |
| Install package and save as a dependency | `npm i [package name] -d/--save`   |
| Install package and save as a dev dependency | `npm i [package name] -D/--save-dev`   |
| Uninstall a package locally      | `npm un/uninstall \| rm/remove [package name]`      |
| Update packages if update availabe | `npm update`                             | 
| Check if a package is outdated | `npm outdated`                               | 
| Update all global packages     |`npm update -g`                               | 
| See which global packages need to be updated | `npm outdated -g --depth=0`    | 
| Update a single global package |`npm update -g <package_name>`                |
| List all packages | `npm list \| ls `|
| List all the pacakges with subpackage filter | `npm ls -g --depth 0` |
