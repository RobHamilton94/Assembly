# Noughts and Crosses

Your task for this project is to implement a noughts and crosses game (aka tic-tac-toe) in
Logisim. You will develop a 3x3 game pad, connect it to a full-core CdM-8 system with a
memory-mapped I/O, and write an assembly language program to manage the game. The
full-core CdM-8 system employs separate code and data memory (Harvard architecture), so
your program will need to be written with this in mind.

Each of the 9 cells on the game pad has sufficient electronics to drive a 4x4 pixel LED
display, which can show a cross, or a nought, or an empty space. Each cell also has an
input button that may be used by a human player to play his/her turn in that cell. The
game pad has controller chips that can be used to connect it to the I/O bus of the CdM-8
processor, so that it may control the game.

The design brief contains specifications for aset of devices sufficient to build a game pad,
and a schematic showing how to connect them together. However, you may design and
implement your own game pad if you wish.
