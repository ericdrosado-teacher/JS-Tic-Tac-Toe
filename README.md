# Assigment 1
In this assignment you will use your knowledge of javascript and change the marker of the Computer player to something other than `O`. In order to complete this assignment you must do the following:

- [ ] You will be working with me as a collaborator so you must follow the GitHub Flow
- [ ] Follow the instructions below under `To play game locally` to play the game on your computer 🙂
- [ ] Read the code so you understand the logic 📖
- [ ] Merge your changes to the main branch

[Click here](https://erics-tic-tac-toe.herokuapp.com) to play!

## To play game locally:

+ Clone this repository
+ In the root directory:
```
npm install
npm install -g beefy
npm install -g browserify
browserify src/index.js -o bundle.js
beefy --browserify bundle.js
```
+ Open `http://localhost:9966` in your browser.

## To run tests:

+ In the root directory:
```
npm install testem -g
browserify spec/test.js -o test_bundle.js
testem
```
