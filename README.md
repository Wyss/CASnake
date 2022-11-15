# SyntheSnake

## A DNA Synthesis Simulator

Modified by David Kalish for the Wyss Institute.

## Original README: ##

JavaScript Snake<br/>
By Patrick Gillespie<br/>
License: MIT<br/>
http://patorjk.com/games/snake

This is a DOM-based game of Snake that I wrote in JavaScript a few years back.

Other than the full screen mode demonstrated in the code, it can also be
initialized in div tags within a page. Example:

    var mySnakeBoard = new SNAKE.Board( {
                                            boardContainer: "game-area",
                                            fullScreen: false,
                                            width: 580,
                                            height:400
                                        });

The comments are formatted a little strange because at the time I was playing
around with YUI Doc.

For gamepad support, install AntiMicroX and run while playing game.
For SNES style controller (iBuffalo Classic USB Gamepad, BSDP801), load
config ```antimicrox_snes_config.gamecontroller.amgp```
