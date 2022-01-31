

 <h><b> Required Installations:  </h></b>
- Postman - https://www.postman.com/downloads/
- Newman 
To be able to run Postman collection in command-line interface, you must have Newman installed. The easiest way to install Newman is using NPM. If you have Node.js installed, it is most likely that you have NPM installed as well.
Install newman
$ npm install -g newman This installs Newman globally on your system allowing you to run it from anywhere.
- newman-reporter-htmlextra plugin
you need newman-reporter-htmlextra plugin installed. To globally install the htmlextra package: 
 $ npm install -g newman-reporter-htmlextra
 
<b><h> How to run the test? </h></b>
 
 <b>CLI</b>
 This collection can be run using CLI as follows:
 - npm run <postman_collection> -e <environment> - r htmlextra
 
 <b>Postman GUI</b>
 This collection can be run directly in postman, to run collectoin directly in Postman :
 - Import JSON postman_collection and environment to the Postman .
 - Click collection runner.
 - Choose environment.
 - Click Start Run
 - Wait until process running done.

<b><h> How to add new test or edit existing tests </h></b>
 - Import JSON postman_collection and environment to the Postman.
 - Edit the collection accordingly
 
 

