[![make.fun · u-0xkianno-one-emoji-one-smile-5470751f](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f.svg)](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-emoji-one-smile-5470751f)
[![rank](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/oreo-sol/u-0xkianno-one-emoji-one-smile-5470751f/rank.svg)](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-emoji-one-smile-5470751f)
[![reward](https://make.fun/badge/u-0xkianno-one-emoji-one-smile-5470751f/oreo-sol/u-0xkianno-one-emoji-one-smile-5470751f/reward.svg)](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-emoji-one-smile-5470751f)

Entry for [One Emoji, One Smile](https://make.fun/bounty/u-0xkianno-one-emoji-one-smile-5470751f) on make.fun.

# One Emoji, One Smile

Exactly one emoji — the one most likely to make a stranger smile.

> 🫶

Heart hands: a warm, universal gesture of kindness from a stranger.
It plainly aims to warm the reader, reads instantly at first glance,
needs no language or in-joke, is chosen rather than the default smiley,
and is a kindness gesture — not intimacy, sarcasm or flirtation.

## Files

- `entry.txt` — the entry, written by `main.ts` (not stored in the repo)
- `main.ts` — writes the single emoji to `$MAKEFUN_OUTPUT_DIR/entry.txt`
  (or `/output/entry.txt`), validating it is exactly one emoji of
  1–8 characters, then reads it back and verifies it byte-identical
- `LICENSE` — MIT

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
