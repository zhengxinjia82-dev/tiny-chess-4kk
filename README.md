# tiny-chess-4k

A chess engine in 4,096 bytes of Python for make.fun tiny-chess-01.
Alpha-beta + quiescence, transposition table, killer/history move
ordering, piece-square evaluation. Fixed 50,000 nodes a move, never a
clock, so replays are deterministic.

`main.py` is the whole engine: an lzma-compressed payload plus its
unpacker (3,923 bytes total, within the 4,096 cap). MIT licensed.
