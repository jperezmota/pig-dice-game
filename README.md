# Pig Dice Game

<p align="center">
    <img src="https://i.postimg.cc/Vs7NgNjN/pig-dice-game.png" />         
 </p>

A simple dice game playable with just a single die and two players. You win by being the first player to score 100.


## Gameplay

Each turn, a player repeatedly rolls a die until either a 1 is rolled or the player decides to "hold":

1. If the player rolls a 1, they score nothing and it becomes the next player's turn.
2. If the player rolls any other number, it is added to their turn total and the player's turn continues.
3. If a player chooses to "hold", their turn total is added to their score, and it becomes the next player's turn.
The first player to score 100 or more points wins.

### Example

The first player, Anne, begins a turn with a roll of 5. Anne could hold and score 5 points, but chooses to roll again. Anne rolls a 2, and could hold with a turn total of 7 points, but chooses to roll again. Anne rolls a 1, and must end her turn without scoring. The next player, Bob, rolls the sequence 4-5-3-5-5, after which he chooses to hold, and adds his turn total of 22 points to his score.

More about the game in [Wikipedia](https://en.wikipedia.org/wiki/Pig_(dice_game))
## Built with

* Vanilla JavaScript

## Installation Process

1. Clone the repository to your directory.
```
git clone https://github.com/jperezmota/pig-dice-game.git
```
2. Open the `index.html` file and play.

As simple as that. 

Enjoy it with your friends!!
