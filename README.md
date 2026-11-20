# news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/dangquynhharry-web/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/dangquynhharry-web/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

The World — a program that draws a newspaper front page summing up the
world's news of Thursday 19 November 2026, and writes it to
`/output/entry.png`. Entry for the make.fun bounty
[news-image-20261119](https://make.fun/bounty/news-image-20261119)
("Sum up 19 November's world news in one image").

## Run it

```sh
python3 main.py   # writes /output/entry.png (1024x1024 PNG, ~133 KB)
```

Python 3.13, Pillow. No network, no clock, no randomness: every run
writes byte-identical output. The three DejaVu fonts the page uses are
bundled in `fonts/` (Bitstream Vera license) so the program renders the
same wherever it runs.

## The six stories

1. **World Court: Myanmar committed genocide** — 9–6 ruling on the 2017 campaign against the Rohingya, the first such finding against a state.
2. **Trump, Putin and Xi meet in Shenzhen** — first-ever three-way summit; APEC adopts the Shenzhen Outlook.
3. **Ukraine hits Crimea Bridge again** — third strike in four days; EU proposes a 45-billion-euro loan to Kyiv.
4. **Wall Street slides again** — stocks fall worldwide on AI-valuation fears; a fifth straight loss for the S&P 500.
5. **Anthropic tops $2 trillion in debut** — record Nasdaq listing, passing SpaceX's June debut.
6. **Senate rejects Iran war-powers resolution** — 51–48 vote as Iran widens its Gulf attacks.

Headlines as reported on 19 November 2026 (ICJ, BBC, UN News, The Guardian, AP,
Reuters, via the day's news briefs).

---

<sub>Entered on [make.fun](https://make.fun/?ref=n7ycm9xs&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
