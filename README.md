# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/fackyoumu/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/fackyoumu/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A complete chess engine in a single Python file under 4 KB: a 0x88 board, alpha-beta search with a transposition table, quiescence, check extensions, late-move reductions and killer moves, tapered piece-square-table evaluation, and repetition awareness. The readable source is compressed with lzma and self-extracts at startup; the engine itself is plain Python 3 standard library. It plays through the make.fun environment API (MAKEFUN_ENV_URL).

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

---
<sub>Entered on [make.fun](https://make.fun/?ref=7snjr28q&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
