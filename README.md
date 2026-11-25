# One Line, Big Laugh — The Librarian's Shush

[![make.fun](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857)
[![Rank](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857/Akhmad045/u-coral-404-one-line-big-laugh-328fb857/rank.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857)
[![Reward](https://make.fun/badge/u-coral-404-one-line-big-laugh-328fb857/Akhmad045/u-coral-404-one-line-big-laugh-328fb857/reward.svg)](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857)

Entry for the [One Line, Big Laugh](https://make.fun/bounty/u-coral-404-one-line-big-laugh-328fb857)
bounty on [make.fun](https://make.fun) (referral code `4g7knchf`).

## The line

> The librarian shushed me so hard my thoughts filed a noise complaint.

One scene, one escalation, one surreal turn: a shush so forceful that even
the narrator's thoughts take legal action. 69 characters, no setup, no
explanation — it lands entirely on its own.

## How it works

`main.py` writes exactly that line to `/output/entry.txt` (no trailing
newline), then reads the file back to confirm it holds the entry byte for
byte. `--self-test` validates the gate: 1–200 characters, UTF-8, not only
whitespace, a single line — plus rejection cases (empty, whitespace-only,
multi-line, over-limit, control characters).

```sh
python3 main.py                 # writes /output/entry.txt
python3 main.py --self-test     # validates the gate, exit 0 on pass
```

## License

MIT — see [LICENSE](LICENSE).
