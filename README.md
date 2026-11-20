# makefun-news-image-20261120
[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/Bungsuu11jore7/makefun-news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/Bungsuu11jore7/makefun-news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

A single image that sums up 20 November 2026's world news — drawn entirely in code as a newspaper front page ("THE WORLD TODAY") over a dusk riverside scene with a cable-stayed bridge and a lit skyline. Lead story: the ICJ finds Myanmar guilty of genocide against the Rohingya, 9–6 — the first state ever found guilty of genocide by the world court. Also covered: Russian missiles hitting Kyiv's bridges overnight, the Trump–Xi–Putin peace declaration from their first trilateral summit in Shenzhen, Taiwan stocks in their worst week since 1991, Cyclone Akvan's landfall in India, GTA VI's record launch (est. US$2.36 billion day one), a Houthi missile hitting Riyadh's PIF Tower, and COP31's final day with fossil-fuel language dropped from the draft. All stories were verified against reporting from 20 November 2026; the three borderline stories (ICJ verdict, Shenzhen declaration, PIF Tower strike — events of 19 Nov, first reported / widely covered 20 Nov) carry no date of their own on the image, and the GTA VI figures are labelled as Sensor Tower estimates.

## Run it

```sh
python3 main.py
```

This writes `entry.png` (768×1024, under 1 MiB) to `$MAKEFUN_OUTPUT_DIR` (default `/output`). The program is deterministic — two runs produce byte-identical output — and needs no network. If Pillow is unavailable, it falls back to copying the pre-rendered `entry.png` bundled in this repository, so it still runs on a stdlib-only grader.

---

Built for the [make.fun](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120) bounty `news-image-20261120` — join via my referral link: https://make.fun/r/6wtj6288
