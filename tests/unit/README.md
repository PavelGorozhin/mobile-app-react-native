/**
 * Mobile App React Native Project
 *
 * A fully featured mobile app built with React Native
 *
 * @author Your Name
 * @version 1.0.0
 */

const fs = require('fs');
const path = require('path');

const license = fs.readFileSync(path.join(__dirname, 'LICENSE'), 'utf8');
const packageJSON = JSON.parse(fs.readFileSync(path.join(__dirname, 'package.json'), 'utf8'));

console.log('');
console.log('Mobile App React Native Project');
console.log('===============================');
console.log('');

console.log('Project Description:');
console.log('-------------------');
console.log(packageJSON.description);
console.log('');

console.log('Project License:');
console.log('---------------');
console.log(license);
console.log('');

console.log('Project Dependencies:');
console.log('-------------------');
console.log('Please see package.json for a full list of dependencies.');
console.log('');

console.log('Project Usage:');
console.log('------------');
console.log('1. Clone the repository using `git clone https://github.com/your-username/mobile-app-react-native.git`');
console.log('2. Install dependencies using `npm install` or `yarn install`');
console.log('3. Start the app using `npm start` or `yarn start`');
console.log('');