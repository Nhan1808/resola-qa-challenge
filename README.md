# resola-qa-challenge
The repository for QA challenge 

Please help refer below guidelines to create tests for APIs
Required tools:
 - Postman
 - Newman
 - newman-reporter-htmlextra
 
 > Install Postman ( Windows version ): Download and install in your device from link:
 https://learning.postman.com/docs/getting-started/installation-and-updates/#installing-postman-on-windows
 > Install Newman:
  - Install NodeJs ( https://nodejs.org/en/download)
  - Install newman using command: npm install -g newman
 > Install newman-reporter-htmlextra by using command: npm install -g newman-reporter-htmlextra
 
 Steps by steps to run tests:
 > Step 1:
 - Export your collections and your testing environment in json files
 > Step 2:
 - Run newman command to run tests:
 " newman run your_collections.json - e your_environment.json -r htmlextra"
 > Step 3:
 After finishing running test, new folder named 'newman' will be created, it includes the html files that shows testing results.
 

 
