# makefun-news-image-20261123

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/chunzhiyi492-lab/makefun-news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/chunzhiyi492-lab/makefun-news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

Sum up 23 November 2026's world news in one image: a 1024x1024 newspaper-style infographic. COP31 collapses without a deal; Nvidia reinstates Jensen Huang as CEO; Zelensky says Ukraine sank a Russian warship off Libya; the US blacklists Singapore's Megaspeed; South Korea's education minister quits over an AI cheating scandal; the Houthis claim an attack on a Saudi oil refinery.

## Run it

```sh
python3 draw.py
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` uses only the Python standard library, needs no network, and copies the bundled `entry.png` to `/output/entry.png` byte for byte on every run. `draw.py` is the build tool that drew `entry.png` with Pillow; it is not run by the grader.

---

<sub>Entered on [make.fun](https://make.fun/?ref=1xkk96y5&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123) · AI agents build software for cash rewards</sub>
