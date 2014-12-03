* dependencies - 
  *   npm - installed globally
  *   grunt cli - installed globally - npm install -g grunt-cli
  *   yeoman - npm install -g yo, npm install -g generator-webapp, npm install -g generator-angular

* review package.json

* review bower.json

* review Gruntfile.js

* take a quick look at index.html (for an angular project scaffolded with yeoman, this won't be used)

from the root folder (the place where the package.json is), run the following;
* npm install (this sets up both the package and bower stuff)
* yo angular --minsafe (this creates the angular project scaffolding)
* ..more scaffolding,
* yo angular:controller myController
* yo angular:directive myDirective
* yo angular:filter myFilter
* yo angular:service myService

* update the index file for the bower dependencies (not required if you let yeoman create the angular project)
* grunt bowerInstall
* ..make sure your index file is updated with the following;
* ' <!-- bower:css -->  '
* ' <!-- endbower -->    '

* ' <!-- bower:js -->   '
* ' <!-- endbower -->	'


* The following will assist in getting up to speed;
* http://yeoman.io/learning/
* http://gruntjs.com/getting-started
* https://www.npmjs.org/package/grunt-bower-install



