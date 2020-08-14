# Hangman

<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Build your own game!

## Content
- [Project Description](#project-description)
- [Games](#games)
- [Project Goals](#project-goals)
- [Requirements & Deliverables](#requirements-&-deliverables)

## Project Description
The project is regarding the Hangman game. The logic regarding the input was forked into four main scenarios:

1 Scenario:
- Input is right and in the word: no iteration over failed attempts

2 Scenario:
- Input is right but not in the word
- Iteration over attempts and the HANGMAN

3 Scenario:

-Input is right but letter already guessed

4 Scenario
- Input is wrong (typo etc)

Regarding the choice of the word, it was created by choosing randomly a word from a given list

The final result:

1)Win if world letters length is equal to zero

OR

2)Lost if there are no more attempts left, attempts is equal to zero

Finally, asked if player wants to play again

The is a cycle that keeps asking the user for input if there is no winner or loser yet.

## Games

* Hangman


## Project Goals
During this project you will:
* Create your own git repository. 
* Build your own code from scratch. 
* Put into practice the basic python concepts learned during the week. 

## Requirements & Deliverables
The **mandatory** requirements that this project needs to satisfy are:  
* Your repository must be clean and organized, which means that it must include a *.gitignore* file and a README file, as well as have a well-structured file organization. 
* Your code includes functions and list comprehension

The **mandatory** deliverables that you must turn in are:
* Link to the repository you used while building your project. The repository must include a README.md file with a description of your project and all the files you used to build your game. Remember to commit often!

The **deadline** to turn in the deliverables is Sunday at 23:59. 
