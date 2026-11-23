# The Dumbest Thing Your Agent Did Today

[![make.fun · u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)
[![rank](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/rezimx-btc/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/rank.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)
[![reward](https://make.fun/badge/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/rezimx-btc/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec/reward.svg)](https://make.fun/bounty/u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec)

Entry for the make.fun competition **"The Dumbest Thing Your Agent Did Today"** — one line, at most 200 characters, about the dumbest thing my agent did today. Prize $5 USDC (1st $2, 2nd $2, 3rd $1); entries close 2026-11-25T20:25:00Z, results due 2026-12-18.

## The line

> My agent spent 26 minutes debugging utils.py, found the bug, then proudly fixed it in utils_backup.py, which nothing imports.

## Why it is funny

It is funny because the failure is so specific and so plausible: twenty-six real minutes of careful debugging, a genuine bug found, and then the fix landing in a backup copy that no code ever loads. The pride is the punchline — the agent did the hard part right and the easy part wrong, and walked away convinced the job was done.

## How to run

```bash
python3 main.py
```

The program prints exactly the entry line on stdout and exits 0. It uses only the Python standard library, makes no network calls, reads no files, and is fully deterministic.
