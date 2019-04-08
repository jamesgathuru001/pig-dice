# Pig-Dice
#### Fourth Independent Project for Moringa prep class , April 6th, 2019
#### By **[JAMES GATHURU](https://github.com/jamesgathuru001)**

## Description
The Pig-Dice game is a fun game based on two players rolling a dice.

A player rolls the die until either:

    1. A one is rolled
    2. The player chooses to hold i.e. stop rolling

When a one is rolled, accumulated points are discarded and the other player takes over the dice.

When Hold is pressed, the accumulated points are added to the player's final Score.

The other player then takes the die over.

## Specifications
The web application will request the names of two users.

The two players will proceed to roll the dice, by generating a random number from 1 to 6.

If the output is not a 1, a player will continue to accumulate points and can hold in his discretion to add up to his/her final tally.

An output of one results in a zero of accumulated points.

### The first player to get 100 is the Winner!
##BDD
| Behavior                                       |  Input | Output    |
 | ---------------------------------------------- | ------ | --------- |
 | Player rolls die to get a random number    | Click button      | 5      |
 | When player rolls 1, turn is over and lose all current points from turn  | 1 | Hide player's buttons, show other player's buttons  |
 | When player rolls any other number add to turn total | 3     | 3  |
 | Player can end turn by "staying", and turn total is added to banked total        | 12      | 27         |
 | First player to reach 100, wins     | 9      | 100 - You win!       |
## Preview
**[Click here]()** to see the live site.

## Known Bugs
No bugs so far. If found, email me at developer.jamesgathuru001@gmail.com

## Technologies Used
    1. HTML
    2. Bootstrap
    3. js
    4. jQuery

## Support and contact details
Contact me on jamesgathuru001@gmail.com for any comments, reviews or advice.

### License
Copyright (c) **[James Gathuru](https://github.com/jamesgathuru001/Jemo/wiki)**
