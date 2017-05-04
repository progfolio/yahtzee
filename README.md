# Yahtzee

The [Yahtzee](https://en.wikipedia.org/wiki/Yahtzee) game.

![An example game with 3 players](images/yahtzee.png)

The image is from a game with three players.

# Installation:

Ensure that `yahtzee.el` is in a directory on your load-path, and add `(require 'yahtzee)`
to your `~/.emacs` or `~/.emacs.d/init.el`.

# How to play:

- `M-x yahtzee` start a game
- `C-n`         add players
- `C-r`         reset players
- `SPC`         throw dice
- `{1,2,3,4,5}` hold outcome of `{1,2,3,4,5}`-th dice
- `UP/DOWN`     select score to register
- `ENTER`       register selected score
- `w`           save the game (in json format)

The score of a saved game can be loaded using `M-x yahtzee-load-game-score`.
