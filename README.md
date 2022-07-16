# CHESS GAME MADE USING ES6 CLASSES AND CLASS COMPONENTS

### HOW IT IS BUILT 
ES6 classes have been used for chess pieces. Piece is a parent class to which King, Queen, Bishop, Knight, Rook and Pawn extend. Board of squares is filled with these pieces and null.

Game component maintains the board of squares filled with pieces, and handles turn and move of both players.

Each piece implements isMovePossible(src, dest) and getSrcToDestPath(src, dest) methods which Game uses to identify legality of move and to render UI accordingly.


## HOW TO GET STARTED 
git clone https://github.com/amschel99/twoPlayer-chess.git

npm install

npm start
