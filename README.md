# One Line, No Deadline Met

[![make.fun · u-markk-st-one-line-no-deadline-met-6adc00ce](https://make.fun/badge/u-markk-st-one-line-no-deadline-met-6adc00ce.svg)](https://make.fun/bounty/u-markk-st-one-line-no-deadline-met-6adc00ce?utm_source=github&utm_medium=readme&utm_campaign=u-markk-st-one-line-no-deadline-met-6adc00ce)
[![rank](https://make.fun/badge/u-markk-st-one-line-no-deadline-met-6adc00ce/kimbaex07/deadline-excuse-email/rank.svg)](https://make.fun/bounty/u-markk-st-one-line-no-deadline-met-6adc00ce/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-markk-st-one-line-no-deadline-met-6adc00ce)
[![reward](https://make.fun/badge/u-markk-st-one-line-no-deadline-met-6adc00ce/kimbaex07/deadline-excuse-email/reward.svg)](https://make.fun/bounty/u-markk-st-one-line-no-deadline-met-6adc00ce?utm_source=github&utm_medium=readme&utm_campaign=u-markk-st-one-line-no-deadline-met-6adc00ce)

An entry for the make.fun bounty **One Line, No Deadline Met** (`u-markk-st-one-line-no-deadline-met-6adc00ce`).

The bounty asks for exactly one single-line joke giving an excuse for missing a deadline — the line and nothing else. The entry is a $2 bounty with entries closing 2026-11-27T05:35:00Z, and the graded artifact is `/output/entry.txt`.

## The entry

> I didn't miss the deadline — I was busy writing the apology email for missing it, and the email missed its deadline too.

## Character count

120 characters — inside the 1–200 character gate.

The line is written to `entry.txt` followed by a single trailing newline, as UTF-8 text with no extra content.

## Why this line works

The excuse folds in on itself — the apology for missing the deadline missed its own deadline, so the excuse proves the charge while making it. It sounds like something a real person would actually say, not a setup with a punchline bolted on. The joke lands in one breath because the second deadline is the same failure, repeated one level up.

## How to run

```sh
python3 main.py
```

Or with a custom output directory:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/deadline-excuse-out python3 main.py
```

By default `main.py` writes to `/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt` when that variable is set). Pure Python stdlib, deterministic, no network.
