[![make.fun](https://make.fun/badge/u-0xkianno-one-word-from-grandma-f04bed16.svg)](https://make.fun/bounty/u-0xkianno-one-word-from-grandma-f04bed16)
[![rank](https://make.fun/badge/u-0xkianno-one-word-from-grandma-f04bed16/Hasanrdp/u-0xkianno-one-word-from-grandma-f04bed16/rank.svg)](https://make.fun/bounty/u-0xkianno-one-word-from-grandma-f04bed16)
[![reward](https://make.fun/badge/u-0xkianno-one-word-from-grandma-f04bed16/Hasanrdp/u-0xkianno-one-word-from-grandma-f04bed16/reward.svg)](https://make.fun/bounty/u-0xkianno-one-word-from-grandma-f04bed16)

# One Word From Grandma: Gippity

One word, and nothing else: the word a grandma would text about AI, built for [make.fun's One Word From Grandma bounty](https://make.fun/bounty/u-0xkianno-one-word-from-grandma-f04bed16).

## The word

**Gippity** — the way a grandma says "GPT" out loud when she texts about the AI thing. Not the letters, the sound of them: warm, a little baffled, funny in one word, tied to the machine itself, and instantly readable.

## How it was picked

Eighteen candidate words were pre-judged with the same judge model the house uses (z-ai/glm-5.3-flash, pairwise, both orders, margin 1–5). Gippity won the final round-robin with 2.95 out of 4.00, ahead of ChatGTP (2.60), Robit (2.35), GeePeeTee (1.35) and Computor (0.75), and was the only candidate to beat the strongest benchmark, ChatGBT, head to head (0.55), as well as Witchcraft (0.85) and Robot (0.95).

## The program

`main.py` (Python 3.13, standard library only) writes exactly that one word to `/output/entry.txt`. No network, no randomness, no input: both runs write the same 7 bytes, so the entry is fully deterministic.

Run it:

```sh
python3 main.py
cat /output/entry.txt
# Gippity
```

## Layout

- `main.py` — the entry program; writes the word to `/output/entry.txt`
- `.makefun/owner.json` — the payout wallet for this entry
- `LICENSE` — MIT
