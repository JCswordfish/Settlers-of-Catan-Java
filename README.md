# Settlers of Catan in Java

Below contains a rundown of each file's purpose:

## Networking
- `ClientScreen.java` - Runs the GUI of each player, as well as inputs/outputs.
- `Client.java`, `Server.java`, `ServerScreen.java`, `ServerThread.java`, `Manager.java` - Work together to connect players to the server and manages sending information between them, mainly updates to the situation of the game.

## The Game
- `Game.java` - Manages the workings of the game.

- `Player.java` - Manages player info.

- `Tile.java`, `TileType.java`, `Trade.java`, `Devcard.java`, `Settlement.java` - Game objects (tiles, trade requests, development cards, settlements)


## Data Structures
- `MyArrayList.java`, `MyDLList.java`, `Node.java`:  Helpful and advanced data structures which optimize game performance.





