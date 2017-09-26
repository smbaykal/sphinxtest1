# sphinxtest1


First, install Node Version Manager (NVM)

https://github.com/creationix/nvm#installation


-Then install desired nodejs version.

nvm install v7.2.1


-Update npm using the following command:

npm i npm -g


Required npm installations
Run the following commands as root:

npm install -g webpack
npm install -g bower


Atom Text Editor
In order to install atom text editor go to the following website and download:

rpm package for Centos 7
deb package for Ubuntu
https://atom.io/

Open it with software install and click install.


Required Atom Plugins
In order to install plug-ins for Atom, go to edit->preferences->install

The required plug-ins are as follows:

altgr
jshint
jslint
last-cursor-position
linter-jshint
project-manager
react               ---apm install react
atom-beautify


Required Chrome plug-ins
In order to install plug-ins go to settings->Extensions, go to the end of the list and click to Get more extensions link.


Building and Running the project
Building & Running the project for the first time
Go to the astarus-ui directory, then run the following commands:

npm install
bower install pdfmake
webpack
webpack -w (Automatic builds when the code changes)
npm start
Building & Running the project in general
webpack
webpack -w (Automatic builds when the code changes)
npm start
Note: If a new dependency is added to package.json, you need to run npm install again once.

Do these then read README.md file. There says * `npm run dev` Runs the project with `webpack-dev-server` and serves it on http://localhost:3000

