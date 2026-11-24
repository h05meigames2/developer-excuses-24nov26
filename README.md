[![make.fun](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
[![Rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/h05meigames2/developer-excuses-24nov26/rank.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)
[![Reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3/h05meigames2/developer-excuses-24nov26/reward.svg)](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3)

# One Funny Developer Excuse

A single-line excuse a developer gives when code breaks in production, written for the [Make the AI Judge Laugh: Developer Excuses](https://make.fun/bounty/u-motasimfuad-make-the-ai-judge-laugh-developer-49386be3) bounty on make.fun. It flips the blame: the code never broke — production simply caught up with the TODO the developer left behind years ago and never fixed.

## The program

`main.py` (Python 3, standard library only, no network) holds the excuse as a single string, validates it — exactly one line, between 1 and 200 characters — and writes it to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`), exiting 0 on success.

## The excuse

> The code didn't break in production — production finally read the TODO I left in 2019.

## Run locally

```bash
MAKEFUN_OUTPUT_DIR=/tmp/excuses-out python3 main.py
cat /tmp/excuses-out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).

---
Built for [make.fun](https://make.fun) — referral: `77v1ce78`
