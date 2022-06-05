## Project 1

For this project we used the command line interface to create a number of folders that were listed in a tree like structure. We practiced using the ping command and the break keyboard sequence. We created and executed the JS files using Node.js and VSCode terminal run and debug.

Technologies used for this project include:
- Node.js
- VSCode

The purpose of the project was to gain experince accessing out operating system's CLI, working with CLI commands, wokring with VSCode, and writing and executing server side JS code.

From this project I learned more about my CLI and how server side code works. I also learned how to create things using my CLI.

```
/*
    CIT 281 Project 1
    Name: Olivia Edwards
*/
let days = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];
/*const d = new Date();*/
/*let day = days[d.getDay()];*/


let day = days[new Date().getDay()];
console.log(day);
```
```
/*
    CIT 281 Project 1
    Name: Olivia Edwards
*/

// Returns a random number between min (inclusive) and max (exclusive)
function getRandomInteger(min, max) {
    return Math.floor(Math.random() * (max - min) + min);
}

const alphabet = "abcdefghijklmnopqrstuvwxyz".split("");

let result = "";

let lengthOfOutputString = getRandomInteger(5, 26);

for (let i = 0; i < lengthOfOutputString; i++) {
    result += alphabet[getRandomInteger(0,alphabet.length)];
}

console.log(result);
```
