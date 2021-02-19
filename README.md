**ScrubChess

**-By: Andrew Kahn

**Project Abstract:**
In the past year, there has been a huge explosion in the game of chess, reaching audiences on Youtube, Twitch, and even Netflix with their hit show "The Queen's Gambit". With this in mind, and with chess being a personal interest of mine, I have decided to develop my own chess app. This project requires two main components, a chess interface and a chess engine, both of which will be built from scratch. Initially this app will be built to play chess against the AI only, but human versus human play may be added in the future.

**Project Relevance:**
This project will demonstrate many of the learning objectives of this class. For example, Object-Oriented Design will be critical, as each chess piece and its behavior will need to be represented with classes and objects, and in addition, the chess engine will be using Trees to evaluate the best move. In addition, User Interaction and Software Interface Design are integral to the first component of this project, which is a user interface. Other learning objectives, such as software arcitecture, design patterns, and debugging are also likely to be demonstrated, as this project will be relatively complex.

**Conceptual Design:**
This project will contain two major components, a user interface, and a conventional chess engine. The former of these will be comprised of an HTML page with an embedded JavaScript chessboard. This chessboard will be interactive, being able to respond to clicking and dragging with the mouse. The information used by the chessboard will be contained in a custom data stucture which will also be used by the chess engine to find its next move. The chess engine will use conventional means, as in Tree search, to evaluate the best moves, as opposed to using neural network machine learning, like many new chess engines do. The move search algorithm will take the chessboard data structure as an input, and generate a Tree containing possible sequences of moves, and then search the Tree for the best move. The tree search will use an Alpha-Beta Pruning algorithm to speed up the search process. Multithreading may also be used to speed up the process even further.

