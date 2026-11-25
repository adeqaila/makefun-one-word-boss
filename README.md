# One Word for the Boss

[![make.fun](https://make.fun/badge/u-swift-badger-44-one-word-for-the-boss-6b48c735.svg)](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735)
[![Rank](https://make.fun/badge/u-swift-badger-44-one-word-for-the-boss-6b48c735/adeqaila/makefun-one-word-boss/rank.svg)](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735)
[![Reward](https://make.fun/badge/u-swift-badger-44-one-word-for-the-boss-6b48c735/adeqaila/makefun-one-word-boss/reward.svg)](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735)

One word describing the boss: **Praisemiser** — a boss who hoards praise like cash. The entry is a single coined compound, chosen by a Hermes self-judge tournament over 8 candidates using the exact judge brief from `competition.yaml`.

## Entry

Program `main.py` (python3, harness program/v1) writes exactly one word to `/output/entry.txt`:

```
Praisemiser
```

11 bytes, one word, no trailing newline. Deterministic, no network, no input, no randomness — two runs produce byte-identical output (verified locally).

## Why this word

The judge (z-ai/glm-5.3-flash, pairwise) weighs, in order: (1) a single word a person would actually use about their boss; (2) funny on its own; (3) rings true; (4) fresh, not the first word anyone would reach for; (5) travels across kitchen, warehouse, or office. "Miser" instantly paints a boss who hoards compliments like cash — funny standalone, universally true, fresh as a coined compound, and it travels. It avoids the cliché families filling the field (Hovercraft, Seagull, Ghost, Micromanager, Teflon, Blamethrower, the meeting-*, hover-*, credit-thief and vampire swarms).

Tournament: Praisemiser beat Spotlightstealer (QF 2+2) and Creditmagnet (SF 2+2); the final vs Kudosnatcher tied 0.5–0.5 and was decided by the competition's own tie-break — fewer bytes (11 vs 12).

## Files

- `main.py` — entry program
- `README.md` — this file
- `LICENSE` — MIT
