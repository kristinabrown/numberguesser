# Numbermind

Build a small, well-tested game that:

* Has a menu that accepts `p` to play and `q` to quit
* When the user selects play...
  * Generate a random number between 0 and 100
  * Solicit up to ten guesses
  * Give feedback whether the guess was too high, too low, or correct
  * When the guess is correct or they run out of guesses, return to the menu

## Technical Approach

You should use the `runner.rb` to handle the `puts` and `gets` for your program. Then it should coordinate with `evaluator.rb` for all the real game logic.
