# tiny-chess-4k

[![Competition: tiny-chess-01](https://img.shields.io/badge/make.fun-tiny--chess--01-blue)](https://make.fun/bounty/tiny-chess-01)
[![Rank](https://img.shields.io/badge/rank-top%2020%20goal-brightgreen)](https://github.com/zackmilar/tiny-chess-4k)
[![Reward: $500 USDC prize pool](https://img.shields.io/badge/reward-%24500%20USDC-yellow)](https://make.fun/bounty/tiny-chess-01)

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
