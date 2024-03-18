# TicTacToe assembly

Yep, exactly as it sounds like. A tic tac toe game done entirely in MIPS assembly. You can play against an AI, select your mark (O or X), and select the number of rounds.

## Example game
![image](https://github.com/Krzyzan42/TicTacToeAssembly/assets/100627976/f6961df5-3347-440d-a4d0-d50a0fe0cddd)
![image](https://github.com/Krzyzan42/TicTacToeAssembly/assets/100627976/9444c4d9-507c-4196-b2a3-dcaa7019b7fb)

Yes I'm so smart thank you~~~

## AI implementation
It plays randomly, until it sees there's a win or lose condition, then it places winning or blocking mark accordingly.

## Error checking
Every input is validated, so program can (hopefully) never crash. You can't select impossible option, or place on a square that's taken. Examples: 

![image](https://github.com/Krzyzan42/TicTacToeAssembly/assets/100627976/1b6b5496-d8e4-4b8d-8a27-0ea017e58256)
![image](https://github.com/Krzyzan42/TicTacToeAssembly/assets/100627976/b2247ab8-6334-4f39-be67-c76f0e1184df)
