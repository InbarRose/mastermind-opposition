# mastermind-opposition

an implementation of the mastermind game with various player implementations which compete with each other

### Mastermind the board game

*from wikipedia [link](https://en.wikipedia.org/wiki/Mastermind_(board_game))*

Mastermind or Master Mind is a code-breaking game for two players.

The game is played using:

- a decoding board, with a shield at one end covering a row of four large holes, and twelve (or ten, or eight, or six) additional rows containing four large holes next to a set of four small holes;
- code pegs of six different colors (or more; see Variations below), with round heads, which will be placed in the large holes on the board; and
- key pegs, some colored black, some white, which are flat-headed and smaller than the code pegs; they will be placed in the small holes on the board.

The two players decide in advance how many games they will play, which must be an even number. One player becomes the codemaker, the other the codebreaker. The codemaker chooses a pattern of four code pegs. Duplicates and blanks are allowed depending on player choice, so the player could even choose four code pegs of the same color or four blanks. In the instance that blanks are not elected to be a part of the game, the codebreaker may not use blanks in order to establish the final code. The chosen pattern is placed in the four holes covered by the shield, visible to the codemaker but not to the codebreaker.

The codebreaker tries to guess the pattern, in both order and color, within twelve (or ten, or eight) turns. Each guess is made by placing a row of code pegs on the decoding board. Once placed, the codemaker provides feedback by placing from zero to four key pegs in the small holes of the row with the guess. A colored or black key peg is placed for each code peg from the guess which is correct in both color and position. A white key peg indicates the existence of a correct color code peg placed in the wrong position.

If there are duplicate colours in the guess, they cannot all be awarded a key peg unless they correspond to the same number of duplicate colours in the hidden code. For example, if the hidden code is white-white-black-black and the player guesses white-white-white-black, the codemaker will award two colored key pegs for the two correct whites, nothing for the third white as there is not a third white in the code, and a colored key peg for the black. No indication is given of the fact that the code also includes a second black.

Once feedback is provided, another guess is made; guesses and feedback continue to alternate until either the codebreaker guesses correctly, or twelve (or ten, or eight) incorrect guesses are made.

The codemaker gets one point for each guess a codebreaker makes. An extra point is earned by the codemaker if the codebreaker doesn't guess the pattern exactly in the last guess. (An alternative is to score based on the number of colored key pegs placed.) The winner is the one who has the most points after the agreed-upon number of games are played.

## Authors / Creators / Credits

* **Inbar Rose** - *Owner* - [InbarRose](https://github.com/InbarRose)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
