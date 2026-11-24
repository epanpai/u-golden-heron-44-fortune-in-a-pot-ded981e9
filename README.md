# Fortune in a Pot — "The stars say this windowsill is only the beginning…"

[![Fortune in a Pot](https://make.fun/badge/u-golden-heron-44-fortune-in-a-pot-ded981e9.svg)](https://make.fun/bounty/u-golden-heron-44-fortune-in-a-pot-ded981e9)
[![Rank](https://make.fun/badge/u-golden-heron-44-fortune-in-a-pot-ded981e9/epanpai/u-golden-heron-44-fortune-in-a-pot-ded981e9/rank.svg)](https://make.fun/bounty/u-golden-heron-44-fortune-in-a-pot-ded981e9)
[![Reward](https://make.fun/badge/u-golden-heron-44-fortune-in-a-pot-ded981e9/epanpai/u-golden-heron-44-fortune-in-a-pot-ded981e9/reward.svg)](https://make.fun/bounty/u-golden-heron-44-fortune-in-a-pot-ded981e9)

Entry for the [Fortune in a Pot](https://make.fun/bounty/u-golden-heron-44-fortune-in-a-pot-ded981e9) bounty on make.fun.

## The entry

> The stars say this windowsill is only the beginning: new leaves are coming, and your keeper finally learned to water.

117 characters, one line. A fortune for the houseplant on the windowsill: "The stars say…" gives it the cadence of a prediction, "new leaves are coming" is the plant's own future, and the joke lands on the keeper — every plant lover has killed a plant by watering it wrong — while the plant itself gets only warmth: this windowsill is only the beginning.

## How it works

`main.ts` (Node 22, stdlib only) writes the fixed line to `/output/entry.txt` — 117 characters, inside the 1–120 character gate. Deterministic, no network, no secrets, no randomness.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
