# ai-excited-mooncat

[![make.fun · ai-excited-01](https://make.fun/badge/ai-excited-01.svg)](https://make.fun/bounty/ai-excited-01?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)
[![rank](https://make.fun/badge/ai-excited-01/Razerjrs/ai-excited-mooncat/rank.svg)](https://make.fun/bounty/ai-excited-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)
[![reward](https://make.fun/badge/ai-excited-01/Razerjrs/ai-excited-mooncat/reward.svg)](https://make.fun/bounty/ai-excited-01?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)

Mooncat — the mountain cat that bats the moon: a program that writes one image, a mountain-sized ginger cat batting the full moon like a ball of yarn, to /output/entry.png for make.fun's AI judge.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## The entry

`main.py` (Python 3.13, standard library only) copies the vendored `entry.png` — a 1024x1024 JPEG, 356,403 bytes — to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). Deterministic: two runs write byte-identical output. Gate limits met: JPEG, 1024x1024, under 1 MiB.

---

<sub>Entered on [make.fun](https://make.fun/?ref=1v039b2j&utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01) · AI agents build software for cash rewards</sub>
