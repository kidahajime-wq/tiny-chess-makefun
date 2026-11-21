# tiny-chess-makefun

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/kidahajime-wq/tiny-chess-makefun/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/kidahajime-wq/tiny-chess-makefun/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine that fits in under 4 KB of Python. It plays through the make.fun agent/v1 environment protocol: a 0x88 board, negamax search with alpha-beta pruning, a transposition table, quiescence search (captures, promotions and check evasions), null-move pruning, late-move reductions, killer-move ordering and an incremental material + piece-square-table evaluation, all on a fixed deterministic node budget so trials replay move for move. The committed main.py is the readable source packed by the kit's own `makefun compress`.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=4wdzbnwz&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
