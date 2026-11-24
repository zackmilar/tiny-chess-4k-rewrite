# tiny-chess-4k

[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/zackmilar/tiny-chess-4k-rewrite/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/zackmilar/tiny-chess-4k-rewrite/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A chess engine in under 4 KB of Python, built for the
[make.fun tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01).

## Engine

`main.py` is a single-file, standard-library-only engine: 0x88 board,
negamax with alpha-beta, transposition table, killer moves, principal
variation search at the root and inside the search, null-move pruning,
razoring, quiet-move futility pruning, and a capped quiescence search.
Fixed 50,000-node budget per move, iterative deepening, fully
deterministic — no clock, no unseeded randomness.

## License

MIT
