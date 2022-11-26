# react-notes
Having issues with complete-react-course build. 

Unexpected token ;

react-complete-guide$ npm install
ERROR: npm v9.1.2 is known not to run on Node.js v12.0.0. You'll need to upgrade
to a newer Node.js version in order to use this version of npm. This version of
npm supports the following node versions: `^14.17.0 || ^16.13.0 || >=18.0.0`. You
can find the latest version at https://nodejs.org/.

ERROR:
/home/jgdallas/.nvm/versions/node/v12.0.0/lib/node_modules/npm/lib/utils/exit-handler.js:22
  const hasLoadedNpm = npm?.config.loaded
                           ^

SyntaxError: Unexpected token .
    at Module._compile (internal/modules/cjs/loader.js:703:23)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:770:10)
    at Module.load (internal/modules/cjs/loader.js:628:32)
    at Function.Module._load (internal/modules/cjs/loader.js:555:12)
    at Module.require (internal/modules/cjs/loader.js:666:19)
    at require (internal/modules/cjs/helpers.js:16:16)
    at module.exports (/home/jgdallas/.nvm/versions/node/v12.0.0/lib/node_modules/npm/lib/cli.js:76:23)
    at Object.<anonymous> (/home/jgdallas/.nvm/versions/node/v12.0.0/lib/node_modules/npm/bin/npm-cli.js:2:25)
    at Module._compile (internal/modules/cjs/loader.js:759:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:770:10)
    
    
THIS IS WHAT I FOLLOWED TO FIX ALL NODE/NPM issues: 
https://www.freecodecamp.org/news/how-to-update-node-and-npm-to-the-latest-version/

