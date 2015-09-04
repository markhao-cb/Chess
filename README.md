# Chess

![alt tag](http://res.cloudinary.com/dypfv4yqq/image/upload/v1441177127/Screen_Shot_2015-09-01_at_11.56.55_PM_c7rkqc.png)

## Description

Ruby implementation of chess. Playable in the command line.


## Features

 * Maximizes code DRYness
   * Pieces inherit from base piece class
 * Responsive interface
   * $stdin.getch method and [cursor logic][cursor] enables players to navigate the board
   with the w, a, s, and d keys
   * Highlights valid moves based on cursor position
 * Utilizes the Null Object Pattern for empty squares
   * [Empty square][empty] class redefines piece methods to provide an appropriate response
   to interactions as opposed error messages

[cursor]: ./display.rb
[empty]: ./empty_square.rb


## Instructions

Clone this repository to a local directory. ```cd``` into the repository. Run
```ruby board.rb```. On your turn, navigate the board with the w, a, s, and d keys. 
Select a piece with the enter key, navigate to where you would like to move, 
and confirm the move with the enter key.
