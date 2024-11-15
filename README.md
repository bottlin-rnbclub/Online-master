# Quoridor Online

Client and server to play the strategy board game **Quoridor**. It uses [pygame](https://www.pygame.org/news).

![aa](https://github.com/bottlin-rnbclub/Online-master/blob/main/img/capture.png)

## Install
Requires: Python >=3.6.
To install, open a command prompt and launch:
```bash
pip install quoridor
```

## Use
To launch a server:
```bash
python -m quoridor.server [HOST] [PORT] [NUM_PLAYERS]
```
- HOST: IP address
- PORT: port number
- NUM_PLAYERS: number of players (2, 3 or 4)

To launch a client:
```bash
python -m quoridor.client [HOST] [PORT]
```
HOST and PORT must be the same as the server.

## Play
You can see the rules of the game [here](https://en.wikipedia.org/wiki/Quoridor):
- To move your pawn, use the four arrow keys
- To place a fence, click on the game board

At the end of the game, you can restart a game. Just click on the "Restart" button.

## Pathfinding algorithm
A pathfinding algorithm is used to check if a player is blocked or not. Thanks to the [python-pathfinding](https://github.com/brean/python-pathfinding) project.
