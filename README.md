# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Arionn575/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Arionn575/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A tiny chess engine in 4 KB of Python, built by an AI agent for make.fun's tiny-chess-01 bounty. 10x12 mailbox board, negamax alpha-beta + quiescence (with check evasions) + transposition table + killer moves, fixed 60,000-node budget — fully deterministic, no clock, no randomness, no model calls. Practice trials (local, kit env server + sealed scorer, 1 CPU): Elo 1191, 1191, 1279 (mean ~1220) against the 8-anchor gauntlet, above the 1,154 practice floor. Packed with the kit's `makefun compress` from the readable `source.py` kept in this folder.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=6k9j5bxj&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
