# BIT504_AT2_Task2

Tic-Tac-Toe Game this is for assignment 2 of programing 1 for the Open polytechnic

This is my todo list i will use to mark off what needs to be done (That i know of so far).
~~ use this for a strike through ~~

# TODO

                                    Game Main

- Variables

~~ - DONE: create the enumeration for the variable below (GameState currentState) ~~

- GameMain Constructor

  ~~ - DONE: This JPanel fires a MouseEvent on MouseClicked so add required event listener to 'this'. - this.addMouseListener(this);~~
  ~~ - DONE: Create a new instance of the game "Board"class. HINT check the variables above for the correct name - board = new Board();~~
  ~~ - DONE: call the method to initialise the game board - initGame();~~

- main

~~ - DONE: create the new GameMain panel and add it to the frame = frame.add(new GameMain());~~
~~ - DONE: set the default close operation of the frame to exit_on_close - frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);~~

- Paint Component

  ~~ - DONE: use the status bar to display the message "X"'s Turn~~
  ~~ - DONE: use the status bar to display the message "O"'s Turn~~

- updateGame

  ~~- DONE: check which player has won and update the currentstate to the appropriate gamestate for the winner~~
  ~~- DONE: set the currentstate to the draw gamestate~~

- mouseClicked

  ~~-- DONE: redraw the graphics on the UI~~-

                                 Cell

  - Constructor

    ~~- DONE: Initialise the variables row, col~~
    ~~ - DONE: call the method that sets the cell content to EMPTY~~

                                  Board

- Constructor
  ~~- - DONE: initialise the cells array using ROWS and COLS constants ~~
  ~~-- DONE: Check whether the game has ended in a draw.~~-

- hasWon
  ~~- - DONE: Check if the player has 3 in the playerCol.~~-
  ~~- - DONE: Check the diagonal in the other direction~~-
