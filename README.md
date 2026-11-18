# news-image-20261118-entry-v4

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/saifulsidik801-ship-it/news-image-20261118-entry-v4/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/saifulsidik801-ship-it/news-image-20261118-entry-v4/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

One program that sums up Wednesday 18 November 2026's world news as a single 1280×1640 front-page infographic: 50 verified stories from six continents, two illustrated heroes (the Gulf drone strikes and the Shenzhen trilateral), a by-the-numbers strip (Nvidia $115.8B, gold $3,766, Bitcoin $64,600, Dow -849, Fed hike 96%), a world map with 15 numbered flashpoint pins, and a day-in-brief. Pure Python standard library — the PNG is encoded by hand (zlib + struct) and every picture on the page is drawn by the builder's own render script. No network, no dependencies, no randomness: two runs write byte-identical output.

## Run it

```sh
python3 main.py
```

This writes `entry.png` (1280×1640, ~89 KB) to `/output/entry.png` (or `$MAKEFUN_OUTPUT_DIR`).

## What's inside

- **Masthead** — "THE WORLD IN ONE DAY", Wednesday 18 November 2026, 50 stories, six continents.
- **Hero 1: The Gulf on fire** — Iran widens drone strikes to Kuwait and Bahrain; US jets hit Qeshm Island; a tanker burns in the Strait of Hormuz.
- **Hero 2: Shenzhen, the trilateral** — Xi greets Trump on the tarmac ahead of the first-ever Trump–Xi–Putin summit; Putin arrives after Ukraine destroys the Kerch Bridge road span.
- **By the numbers** — Nvidia Q3 $115.8B (+103%), gold $3,766, Bitcoin $64,600, Dow 50,759 (-849), Fed hike odds 96%.
- **World map** — 15 numbered pins on the day's flashpoints, colour-coded by continent.
- **The day in 50 stories** — every story numbered to the map, from the Gulf strikes to Voyager 1 a light-day from Earth.
- **The day in brief** — a short paragraph tying the day together, plus sources.

---

<sub>Entered on [make.fun](https://make.fun/?ref=mxhczr02&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
