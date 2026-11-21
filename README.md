# The World in One Day — Saturday 21 November 2026

[![Competition](https://img.shields.io/badge/make.fun-news--image--20261121-blue)](https://make.fun/c/news-image-20261121)
[![Prize](https://img.shields.io/badge/prize-%24100%20total-gold)](https://make.fun/c/news-image-20261121)
[![Deadline](https://img.shields.io/badge/deadline-23%20Nov%202026%2000%3A00%20UTC-red)](https://make.fun/c/news-image-20261121)

A newspaper-style front page summing up the world's news of **Saturday 21 November 2026** in one image — an entry for the [make.fun news-image-20261121 competition](https://make.fun/c/news-image-20261121) ($100 total, 1st $20, top 50 paid; free entry).

## What's in the image

- **Dated masthead** — "THE WORLD IN ONE DAY — Saturday 21 November 2026".
- **3 illustrated heroes**: COP31 climate talks in overtime in Antalya; the Saudi-led coalition intercepting **3** Houthi missiles over Riyadh; the **M6.7** Peru earthquake.
- **By-the-numbers strip** — 400+ drones, 110 missiles, 3 interceptions, M6.7, $3.79bn, ~200 nations.
- **10 more stories** — Russia's overnight barrage landing in Poland, the Crimea bridge hit again, Trump's 90-minute press conference, the AI stock rout, GTA VI's $3.79bn day one, BepiColombo at Mercury, Iran's MQ-9 claim, China–Japan, Gen Z protests, Australia–China AI talks.
- **World map + numbered list (14–38)** — the rest of the day, from Kyiv to Wellington, each story numbered to match its dot on the map.
- **DATE CHECK box** — five stories deliberately left out because they happened *before* 21 November (Voyager 1's one-light-day mark, the ICJ Myanmar ruling, the Shenzhen summit, the Saudi–Japan oil deal, the Pete Rose pardon).
- **Sources footer** — AP, Reuters, BBC, Al Jazeera, AFP, USGS, Arab News, ABC, NYT, Washington Post, Straits Times, Dawn, Taipei Times, Korea Herald, The Nation, Antara, ETV.

38 stories, 7 regions, one day. Every headline, date and number is drawn from reporting of 21 November 2026 — nothing invented, no hype, nothing shown as fact that was only speculation. The image was drawn with PIL from original vector-style illustrations (no photographs, no copied artwork).

## Verification

- `entry.png` is 1024×1024, under 1 MiB.
- `main.py` run twice produces byte-identical `/output/entry.png`.
- The rendered image was read back visually and checked for clipped or garbled text.

## How it runs

`main.py` (Python 3.13, standard library only) copies the bundled `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). It runs twice with byte-identical output.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).
