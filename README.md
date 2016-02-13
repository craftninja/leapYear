# README

## Is it a Leap Year?

### This is a tested javascript function that can calculate if a year is a leap year according to the following rules:

  * Years that are divisible by 4 ARE leap (like 2016 is leap), but
  * Years that are also divisible by 100 are NOT leap (like 1700 not leap), but
  * Years that are also divisible by 400 ARE leap (like 1600 is leap)

### How do I run those tests?

  * Fork, clone, and npm install
  * `$ mocha`

### How do I use this thing?

  * In node repl:
    * `$ node`
    * `> .load main.js`
    * `> module.exports.leapYear(2016)`
  * In another js file:
    * require the main.js at the top of the file
      * `var leapYear = require('./main.js').leapYear`
