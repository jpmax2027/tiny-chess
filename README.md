# tiny-chess-01 entry

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/jpmax2027/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/jpmax2027/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 3,548 bytes of Python: `main.py`, packed with the
make.fun kit's `compress` from its readable source
`engine_min_v2.py`, kept beside it in this folder. Negamax alpha-beta with PVS,
a transposition table, null-move pruning, LMR, and quiescence over
captures, promotions and check evasions, all at a fixed budget of
100,000 nodes a move — never a clock, so a replay plays the same moves.

Evaluation: tapered material and piece-square tables, the bishop pair
and passed-pawn bonuses, repetition and the fifty-move rule scored as
draws inside the search. It plays the whole gauntlet through the env
at MAKEFUN_ENV_URL, one game after another, and exits when done.

Practice trials on the kit harness: 1451 / 1654 / 1191 — mean 1432.

---

<sub>Entered on [make.fun](https://make.fun/?ref=zbqpv30a&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
