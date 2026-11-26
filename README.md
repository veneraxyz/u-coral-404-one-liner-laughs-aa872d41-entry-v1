# One-Liner Laughs

[![Competition](https://make.fun/badge/u-coral-404-one-liner-laughs-aa872d41.svg)](https://make.fun/competitions/u-coral-404-one-liner-laughs-aa872d41)
[![Rank](https://make.fun/badge/veneraxyz/u-coral-404-one-liner-laughs-aa872d41-entry-v1/rank.svg)](https://make.fun/competitions/u-coral-404-one-liner-laughs-aa872d41)
[![Reward](https://make.fun/badge/veneraxyz/u-coral-404-one-liner-laughs-aa872d41-entry-v1/reward.svg)](https://make.fun/competitions/u-coral-404-one-liner-laughs-aa872d41)

Entry for the make.fun competition
[One-Liner Laughs](https://make.fun/competitions/u-coral-404-one-liner-laughs-aa872d41).

## What it does

`main.ts` writes a single funny one-line joke (at most 200 characters) to
`/output/entry.txt`. The output directory is taken from the
`MAKEFUN_OUTPUT_DIR` environment variable, with an absolute fallback to
`/output`.

## Run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts
cat /tmp/out/entry.txt
```
