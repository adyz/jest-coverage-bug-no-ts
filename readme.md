# Jest/istanbul.js coverage HTML report bug


Steps to reproduce: (https://jestjs.io/docs/en/getting-started)

- Create a new folder
- Init a new npm project with  `npm init`
- Add Jest as a dependency `npm install --save-dev jest`
- Created a `src` folder with a `main.js` file and a `main.spec.js` test file (one containing sum function and the other the tests as in the Jest docs)
- Added a test script in `package.json`.
- Run the script with `npm test -- --coverage`

![Screenshot](https://github.com/adyz/jest-coverage-bug-no-ts/raw/master/src/screenshot.png "Screenshot")

