# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/jzy050809-cloud/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/jzy050809-cloud/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 3,577-byte chess engine in Python 3.13, standard library only. 0x88 board, full legal moves, negamax alpha-beta with iterative deepening to a fixed 45,000-node budget, quiescence, MVV-LVA and killer ordering, piece-square tables, bishop pair and passed-pawn bonuses. Deterministic: no clock, no randomness, no network except the make.fun env.

## Run it

```sh
python3 -P -s main.py
```

The trial sets MAKEFUN_ENV_URL; the engine talks to it with POST /game, /move and /resign.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
