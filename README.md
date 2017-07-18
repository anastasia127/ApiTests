# ApiTests
## Synopsis
API tests for GIT commit
## Synopsis
Prerequisites Nodejs and NPM (to check node -v; npm -v)
1. install Newman globally 
npm install - g newman
2.download json file from the repo
3. newman run your.json  (newman run https://www.getpostman.com/collections/be150de902feae0fc416)
4. to run from CI  - path/to/node path/to/newman newman run https://www.getpostman.com/collections/be150de902feae0fc416
