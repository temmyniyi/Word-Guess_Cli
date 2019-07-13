# Word-Guess_Cli
A word guess game using the command line interface.
This word guess game prompts the user to guess the name of the popular House in Game of Thrones that the program has generated.
The Houses are stored in an array that is selected at random by the game and this is carried out utilizing the command line interface that nodeJS provides and uses the inquirer function that allows the user to input letters on the command line interface.

## Installation
You can install and run with NPM. Simply open your terminal and type the following commands:
```
$ git clone https://www.github.com/adnanyousef/word-guess-cli.git
$ cd word-guess-cli
$ npm install
```
Then, start the game with:
```
$ node index.js
```
Alternatively, to install system-wide (so that you don't have to be in the directory to run the app), just run:
```
$ npm link
```
This will make the command `word-guess-cli` available to you anywhere in your terminal! No need `cd` into this git repo to run the app.

## How To Play
1. After launching the game, you will see some blanks. Each represents a letter from the random word.
2. Type a letter to guess if it is in the random word.
3. Each time you guess an incorrect letter, your "Guesses Remaining" will reduce by 1. Once this reaches zero, you lose!
4. If you guess the random word before exhausting your guesses remaining, you win!
5. At the win/loss screen, you may play again by hitting the enter key, or you can exit by typing "n" or "no."