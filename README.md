node ➜ /workspaces/angular-docker-dev-env (master) $ ng version

     _                      _                 ____ _     ___
    / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
   / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
  / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
 /_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
                |___/
    

Angular CLI: 13.0.3
Node: 16.20.0
Package Manager: npm 8.19.4
OS: linux x64

Angular: 
... 

Package                      Version
------------------------------------------------------
@angular-devkit/architect    0.1300.3 (cli-only)
@angular-devkit/core         13.0.3 (cli-only)
@angular-devkit/schematics   13.0.3 (cli-only)
@schematics/angular          13.0.3 (cli-only)
    
node ➜ /workspaces/angular-docker-dev-env (master) $ hostname
9f823178786d


node ➜ /workspaces/angular-docker-dev-env (master) $ ng build
The build command requires to be run in an Angular project, but a project definition could not be found.

node ➜ /workspaces/angular-docker-dev-env (master) $ cd test-app


node ➜ /workspaces/angular-docker-dev-env/test-app (master) $ ng build
An unhandled exception occurred: Cannot find module '@angular-devkit/build-angular/package.json'


node ➜ /workspaces/angular-docker-dev-env/test-app (master) $ npm install
...
added 1028 packages, and audited 1029 packages in 6m
90 packages are looking for funding
  run `npm fund` for details
73 vulnerabilities (2 low, 43 moderate, 22 high, 6 critical)


node ➜ /workspaces/angular-docker-dev-env/test-app (master) $ ng build
✔ Browser application bundle generation complete.
✔ Copying assets complete.
✔ Index html generation complete.

Initial Chunk Files           | Names         |      Size
main.3b55947f13cc1cfc.js      | main          | 132.06 kB
polyfills.ae4b6e77e1b6e989.js | polyfills     |  36.20 kB
runtime.b060a325609bec71.js   | runtime       |   1.04 kB
styles.ef46db3751d8e999.css   | styles        |   0 bytes

                              | Initial Total | 169.30 kB

Build at: 2024-09-19T05:22:42.069Z - Hash: 53a1d6685ac0ca38 - Time: 87301ms


node ➜ /workspaces/angular-docker-dev-env/test-app (master) $ ng serve
✔ Browser application bundle generation complete.

Initial Chunk Files   | Names         |      Size
vendor.js             | vendor        |   1.83 MB
polyfills.js          | polyfills     | 339.08 kB
styles.css, styles.js | styles        | 212.39 kB
main.js               | main          |  51.07 kB
runtime.js            | runtime       |   6.85 kB

                      | Initial Total |   2.43 MB

Build at: 2024-09-19T05:23:47.481Z - Hash: 6b8b846ba61a3d06 - Time: 28331ms

** Angular Live Development Server is listening on localhost:4200, open your browser on http://localhost:4200/ **
