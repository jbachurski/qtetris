# qtetris

## Description

*This is a project originally developed in 2016, when I was in middle school, as a school project.*

The main feature is a pygame Tetris. There's also a simple AI which was trained based on a blog (which I've forgotten) about a genetic algorithm for a single-layer perceptron with some simple features.

The main entry point is `python app_player.py`.

The usage of Cython for running the game is somewhat broken, but after installing `pygame` it should run a self-playing game (last checked on Python 3.10). There are some keyboard controls.

- `Up` - rotate tetrimino
- `Space` - swap tetrimino with next
- `P` - pause
- `R` - reset game
- `N` - enable/disable delay between ticks
- `F` - fast delay
- `S` - slow delay
- `Q` - quit
- `A` - enable AI

By default, the AI is enabled and it is in fast delay mode.

## Original description

A tetris game. Also includes a self-learning AI, based on a Evolving Neural Network.

Requires pygame for graphics to function.

*Outdated:* ~~Note: If you do not have Python 3.5 and 64-bit Windows, replace the .pyd files with the respective files of name ...py.py from their folders. That is gamecls-=-.pyd -> gameclspy.py, with its name changed to gamecls.py, for example.~~

![image](https://user-images.githubusercontent.com/25066148/189497691-5ff9bfba-5d8a-41fa-b5e7-437941128f34.png)
